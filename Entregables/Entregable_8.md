# Entregable 8

## Introducción y Contextualización del Prototipo

### Descripción breve del proyecto:
El proyecto consiste en el diseño y construcción de una bomba de jeringa de microfluidos de bajo costo, diseñada para aplicaciones en laboratorios de investigación y llenado preciso de cápsulas de medicamentos. El prototipo tiene control preciso de caudal y tiempo, una interfaz que incluye un rotary encoder y una pantalla OLED, además de un diseño modular y de hardware abierto que permite su uso en entornos con recursos limitados.

### Problemática abordada:
En muchos laboratorios, especialmente en regiones con recursos escasos, no hay equipos accesibles para manejar fluidos en pequeñas cantidades con precisión. Esto dificulta investigaciones y experimentos que requieren dosificación controlada. Los dispositivos disponibles en el mercado son costosos y poco personalizables.

### Objetivos de la fase de integración:
- Integrar todos los componentes del prototipo para su funcionamiento conjunto.
- Verificar que la interfaz de usuario (rotary encoder y pantalla OLED) permita ajustar y visualizar parámetros de caudal y tiempo.
- Asegurar que el motor N20 y el mecanismo de guía lineal trabajen sincronizados para un movimiento preciso.
- Realizar pruebas que evalúen la funcionalidad y desempeño del prototipo.

---

## Componentes del Prototipo

### Lista de componentes principales:
1. Arduino Uno: Controlador principal del sistema.
2. Motor N20 con husillo: Responsable del movimiento preciso del émbolo de la jeringa.
3. Controlador A4988: Regula el movimiento del motor.
4. Pantalla OLED 128x64: Muestra el menú y los parámetros.
5. Rotary Encoder: Ajusta valores de caudal y tiempo.
6. Jeringa estándar: Contenedor del fluido.
7. Guía lineal y pusher block: Aseguran la precisión del movimiento del émbolo.
8. Fuente de alimentación: Proporciona energía al sistema.
9. Switch de encendido/apagado: Activa o desactiva el dispositivo.

### Interacción entre componentes:
- El rotary encoder envía señales al Arduino Uno, que procesa los datos y ajusta los parámetros en la pantalla OLED.
- El Arduino Uno controla el driver A4988, que regula el movimiento del motor N20 para empujar o retraer el émbolo.
- La guía lineal asegura un movimiento estable y preciso del motor.
- El switch de encendido/apagado activa el sistema completo.

### Diagrama de integración:
![Diagrama de integración](https://github.com/user-attachments/assets/8cab3f50-38dd-48ee-8f58-c05842654785)

---

## Proceso de Integración

### Plan de integración:
Se ensamblaron los componentes mecánicos y electrónicos. Los ajustes iniciales incluyeron la configuración del controlador A4988 para el motor N20 y pruebas para asegurar la funcionalidad de la pantalla OLED y el rotary encoder. 

### Desafíos y ajustes realizados:
No se contaba con una guía lineal, por lo que se utilizó un actuador lineal compuesto por un motor DC como reemplazo. Además, se cambió el driver del motor paso a paso A4988 por un DRV8833, que permitió controlar la velocidad del motor DC.

### Revisión de compatibilidad y sincronización:
Durante las pruebas, se ajustó el sistema para garantizar que el DRV8833 pudiera controlar correctamente el motor DC y modificar su velocidad, lo que permitió lograr avances más lentos y controlados.

---

## Pruebas y Verificación

### Descripción de pruebas funcionales:
Se realizaron pruebas para verificar que:
1. El DRV8833 controlara la velocidad del motor DC de manera adecuada.
2. La interfaz con el rotary encoder y la pantalla OLED mostrara los parámetros correctamente.
3. El sistema mecánico pudiera empujar el émbolo de manera funcional.

### Resultados de pruebas:
- Se logró controlar la velocidad del motor DC utilizando el driver DRV8833, aunque la inestabilidad del motor representa una limitación importante.
- El émbolo de la jeringa se empuja de manera funcional, pero con menor precisión debido a la ausencia de un motor paso a paso.

Videos de las pruebas:


 https://github.com/user-attachments/assets/a46dafdb-d020-4827-9157-654ff3cd96fc

 


### Evaluación de desempeño:
Aunque el sistema es funcional, la inestabilidad del motor DC afecta la precisión y el control necesario para aplicaciones microfluídicas. Esto será mejorado en fases futuras.



## Conclusiones y Próximos Pasos

### Resumen de logros:
Se integraron los componentes básicos del prototipo, logrando un sistema funcional para empujar el émbolo de las jeringas. El motor DC, aunque inestable, permite controlar la velocidad y realizar pruebas preliminares.

### Aspectos por mejorar:
- Adquirir el motor paso a paso pendiente para mejorar la precisión y estabilidad del sistema.
- Optimizar el uso del rotary encoder y la pantalla OLED para permitir el ajuste directo de parámetros.

### Siguientes fases del desarrollo:
- Implementar el ajuste de parámetros desde el rotary encoder y la pantalla OLED.
- Aplicar los valores ajustados al control del motor DC.
- Sustituir el motor DC por el motor paso a paso una vez que esté disponible para aumentar la precisión y la confiabilidad del sistema.

