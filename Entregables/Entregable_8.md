# Entregable 8
# Entregable 8

## Introducción y Contextualización del Prototipo

### Descripción breve del proyecto:
El proyecto consiste en el diseño y construcción de una bomba de jeringa de microfluidos de bajo costo, diseñada para aplicaciones en laboratorios de investigación y llenado preciso de cápsulas de medicamentos. El prototipo cuenta con un control preciso del caudal y tiempo, una interfaz basada en un rotary encoder y una pantalla OLED, y un diseño modular y de hardware abierto para facilitar su uso en entornos con recursos limitados.

### Problemática abordada:
En muchos laboratorios, especialmente en regiones con bajos recursos, no se dispone de equipos accesibles para el manejo preciso de fluidos en pequeñas cantidades. Esto limita la capacidad de realizar investigaciones y experimentos que requieren precisión en la dosificación y manejo de fluidos. Además, los dispositivos disponibles en el mercado son costosos y difíciles de personalizar.

### Objetivos de la fase de integración:
- Integrar todos los componentes del prototipo para asegurar su funcionamiento conjunto.
- Verificar que la interfaz de usuario (rotary encoder y pantalla OLED) permita ajustar y visualizar correctamente los parámetros del caudal y tiempo.
- Garantizar que el motor N20 y el mecanismo de guía lineal trabajen de manera sincronizada para un movimiento preciso.
- Realizar pruebas para evaluar la funcionalidad y desempeño general del prototipo.

---

## Componentes del Prototipo

### Lista de componentes principales:
1. **Arduino Uno**: Controlador principal del sistema.
2. **Motor N20 con husillo**: Responsable del movimiento preciso del émbolo de la jeringa.
3. **Controlador TMC2209**: Permite controlar el motor con precisión y bajo ruido.
4. **Pantalla OLED 128x64**: Interfaz de visualización para el menú y los parámetros.
5. **Rotary Encoder**: Permite al usuario ajustar valores como caudal y tiempo.
6. **Jeringa estándar**: Contenedor de fluido.
7. **Guía lineal y pusher block**: Aseguran la estabilidad y precisión del movimiento del émbolo.
8. **Fuente de alimentación**: Alimenta el sistema.
9. **Switch de encendido/apagado**: Controla la activación del dispositivo.

### Interacción entre componentes:
- El **rotary encoder** envía señales al **Arduino Uno**, que procesa los datos y ajusta los parámetros mostrados en la **pantalla OLED**.
- El **Arduino Uno** controla el **TMC2209**, que regula el movimiento del **motor N20** para empujar o retraer el émbolo de la jeringa a velocidades específicas.
- La **guía lineal** asegura que el movimiento del motor sea lineal y estable.
- El **switch de encendido/apagado** permite activar el sistema completo de manera segura.

### Diagrama de integración:
![image](https://github.com/user-attachments/assets/8cab3f50-38dd-48ee-8f58-c05842654785)

### Diagrama de integración:

## Proceso de Integración
### Plan de integración:
### Desafíos y ajustes realizados:
### Revisión de compatibilidad y sincronización:

## Pruebas y Verificación
### Descripción de pruebas funcionales:
### Resultados de pruebas: 
### Evaluación de desempeño:

## Conclusiones y Próximos Pasos
### Resumen de logros:
### Aspectos por mejorar: 
### Siguientes fases del desarrollo: 
