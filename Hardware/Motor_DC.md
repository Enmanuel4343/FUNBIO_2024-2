## Codigo de conexion y verificaión del funcionamiento del Motor DC

#define IN1 3
#define IN2 4

void setup() {
 pinMode(IN1, OUTPUT);
 pinMode(IN2, OUTPUT);

}

void loop() {
  
 // motor 1 run 50% speed in FWD for 5 seconds
  analogWrite(IN1,0);
  digitalWrite(IN2, LOW);

  delay(5000);
}