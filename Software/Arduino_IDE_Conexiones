CODIGO DE CONEXIONES Y FUNCIONAMIENTO DEL MOTOR DC BAJO UN DRIVER (DRV8833)

// Pines de conexión
// MOTOR 1 DC
#define IN1 3
#define IN2 4

void setup() {
 pinMode(IN1, OUTPUT);
 pinMode(IN2, OUTPUT);
}

void loop() {
 // motor dc se mueve durate 5 segundos
  analogWrite(IN1,0);
  digitalWrite(IN2, LOW);
  delay(5000);
}
CODIGO DE CONEXIONES Y FUNCIONAMIENTO DEL OLED Y ENCODER 
#include <Wire.h>
#include <Adafruit_GFX.h>
#include <Adafruit_SSD1306.h>

#define SCREEN_WIDTH 128
#define SCREEN_HEIGHT 64
#define OLED_RESET -1
Adafruit_SSD1306 display(SCREEN_WIDTH, SCREEN_HEIGHT, &Wire, OLED_RESET);

#define ENCODER_CLK 5
#define ENCODER_DT 6
#define ENCODER_SW 7

int menuIndex = 0;
bool adjustingValue = false;
int caudal = 0;  // En ml/s
int tiempo = 0;  // En segundos
int lastStateCLK = HIGH;
bool menuNeedsUpdate = true;

const char* menuItems[] = {"Caudal", "Tiempo", "Proceso"};
const int numOfItems = sizeof(menuItems) / sizeof(menuItems[0]);

void setup() {

  display.begin(SSD1306_SWITCHCAPVCC, 0x3C);
  display.clearDisplay();
  
  pinMode(ENCODER_CLK, INPUT);
  pinMode(ENCODER_DT, INPUT);
  pinMode(ENCODER_SW, INPUT_PULLUP);

  showStaticBackground();
}

void loop() {
  handleEncoder();

  if (adjustingValue) {
    adjustValue();
  } else if (menuNeedsUpdate) {
    showStaticBackground();  
    navigateMenu();
    menuNeedsUpdate = false;
  }
}

void showStaticBackground() {
  display.clearDisplay();
  display.setTextSize(2);
  display.setTextColor(SSD1306_WHITE, SSD1306_BLACK);  
  display.setCursor(0, 0);
  display.print("MENU:");
  display.drawLine(0, 16, SCREEN_WIDTH, 16, SSD1306_WHITE);
  display.display();
}

void navigateMenu() {
  for (int i = 0; i < numOfItems; i++) {
    display.setTextSize(1);
    display.setCursor(10, (i + 1) * 12 + 16); 
    display.setTextColor(i == menuIndex ? SSD1306_BLACK : SSD1306_WHITE, i == menuIndex ? SSD1306_WHITE : SSD1306_BLACK);
    display.print(menuItems[i]);
  }
  
  display.display();
}

void handleEncoder() {
  int currentStateCLK = digitalRead(ENCODER_CLK);
  
  if (currentStateCLK != lastStateCLK) {
    menuNeedsUpdate = true; 
    if (digitalRead(ENCODER_DT) != currentStateCLK) {
      menuIndex = (menuIndex + 1) % numOfItems; 
    } else {
      menuIndex = (menuIndex - 1 + numOfItems) % numOfItems;  
    }
  }
  lastStateCLK = currentStateCLK;


  if (digitalRead(ENCODER_SW) == LOW) {
    delay(200);  
    if (menuIndex < 2) {
      adjustingValue = true; // Entra en ajuste de "Caudal" o "Tiempo"
    } else {
      showSummary(); // Muestra el resumen de parámetros si selecciona "Proceso"
    }
  }
}

// Ajusta el valor de caudal o tiempo
void adjustValue() {
  display.clearDisplay();
  display.setCursor(0, 0);
  
  if (menuIndex == 0) {
    display.print("Ajustar Caudal (ml/s):");
    display.setCursor(0, 20);
    display.print(caudal);
  } else if (menuIndex == 1) {
    display.print("Ajustar Tiempo (s):");
    display.setCursor(0, 20);
    display.print(tiempo);
  }
  
  display.display();

  int currentStateCLK = digitalRead(ENCODER_CLK);
  if (currentStateCLK != lastStateCLK) {
    menuNeedsUpdate = true;
    if (digitalRead(ENCODER_DT) != currentStateCLK) {
      if (menuIndex == 0) {
        caudal += 10;  // Aumenta caudal
      } else {
        tiempo += 1;  // Aumenta tiempo
      }
    } else {
      if (menuIndex == 0) {
        caudal = max(caudal - 1, 0);  // Disminuye caudal
      } else {
        tiempo = max(tiempo - 1, 0);  // Disminuye tiempo
      }
    }
  }

  lastStateCLK = currentStateCLK;

  // Detecta si se presiona el botón para salir del ajuste
  if (digitalRead(ENCODER_SW) == LOW) {
    delay(200);  // Anti-rebote
    adjustingValue = false; // Regresa al menú principal
    menuNeedsUpdate = true; // Solicita actualización de pantalla
  }
}

// Muestra un resumen de los parámetros configurados
void showSummary() {
  display.clearDisplay();
  display.setTextSize(1);
  display.setCursor(0, 0);
  display.print("Resumen:");
  display.setCursor(0, 12);
  display.print("Caudal: ");
  display.print(caudal);
  display.print(" ml/s");
  display.setCursor(0, 24);
  display.print("Tiempo: ");
  display.print(tiempo);
  display.print(" s");
  display.display();
  delay(3000);  // Espera 2 segundos y regresa al menú principal
  menuNeedsUpdate = true; // Solicita actualización de pantalla
}

