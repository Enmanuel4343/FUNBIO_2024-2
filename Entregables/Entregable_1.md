# Introducción
## 1. Definicion de Open Hardware
Segun Open Hardware, o hardware abierto, es cualquier dispositivo o componente cuyo diseño y planos son accesibles para que cualquiera los use, modifique o fabrique. La idea es que, al igual que el software de código abierto, puedas ver cómo funciona, cambiarlo para adaptarlo a tus necesidades, y compartirlo con otros. Esto fomenta la colaboración, la innovación, y hace que el hardware sea más accesible y personalizable [1].
### Ejemplos Conocidos de Open Hardware
 - Arduino: Placas electrónicas que puedes programar para hacer casi cualquier cosa, desde robots hasta dispositivos de domótica. Sus diseños son abiertos y modificables [2].
 - Raspberry Pi: Una mini computadora de bajo costo utilizada para aprender a programar, proyectos DIY, y más. No es 100% abierta, pero es muy popular en la comunidad [3].
 - Prusa i3: Una impresora 3D cuyo diseño es totalmente abierto, permitiendo que cualquiera la modifique o fabrique sus propias versiones [4].
### ¿Por qué es Importante?
- Personalización: Puedes adaptar el hardware a tus necesidades específicas.
 - Transparencia y seguridad: Puedes revisar y mejorar los diseños.
 - Colaboración e innovación: Más personas pueden contribuir con ideas y mejoras.
 - Ahorro de costos: No necesitas pagar licencias o royalties.

 ## 2. Análasis de la tematica:

### Definición de terminos clave: Microfluidos, Bomba de microfluidos, Bomba de jeringa, Preparación de mezclas

### Desarrollo de la temática:

La microfluídica es el campo de la ciencia dedicada al trabajo en escalas micrométricas, referidas a los 10 a la menos 6 metros, escalas sumamente pequeñas.

Tambien se acepta la definición enfocada en el aprovechamiento de las ventajas que proporcionan el uso y control del fluido a escalas inferios a la milimétrica. Cabe aclarar que las propiedades físicas cambian respecto a la escala convencional y que seria incorrecto afirmar que un sistema macroscópico se comportara igual que uno microscópico [5].

Es importante también conocer el porque representa un beneficio trabajar con microfluidos y no fluidos convencionalmente hablando,

Para el correcto estudio de sistemas microfluídicos y de los fluidos con los que se trabajaran, se deben de tener en cuenta principios físicos que si bien en la escala convencional no presentan una gran importancia, a la hora de evaluar fluidos en ínfimas proporciones, se vuelve dominantes y fundamentales, debido a que ayudaran a poder controlar de manera eficiente al fluido.

#### 1) Flujo laminar:

Segun explica (Bharat, 2017, p.492), al trabajarse con dimensiones de canal tan pequeñas, las paredes tienen muy poca distancia entre si, lo cual permite que las particulas del fluido fluyan en capas adyacentes unas con otras.

Se pueden utilizar donde formulas para poder determinar el flujo laminar:

##### Número de Reynolds (Re):

Cuando Re<2300, se afirmar que se está trabajando con un fluido con flujo laminar, caso contrario se está trabajando con un fluido con flujo turbulento, claramente esto depende de los parámetros en los cuales se pondra a el fluido.

[
![SmartSelect_20240916_201025_Adobe Acrobat](https://github.com/user-attachments/assets/241a04ae-544d-46dc-9d83-00d1096c4f5c)
](url)

En donde "ro" s la densidad del fluido, V es la velocidad del fluido corriente, Dh el diametro del canal y "mi" la viscosidad del canal. Por ende se evidencia que la densidad, velocidad y diametro son directamente proporcionales con el Número de Reynolds, mientras que la viscosidad es inversamente proporcional a Re [6].

##### Resistencia del Fluido (R):

![SmartSelect_20240916_203038_Adobe Acrobat](https://github.com/user-attachments/assets/42f3ead6-4b82-44bb-be9e-ff62e38f186b)

En donde "mi" es la viscosidad del fluido, L es la longitud del canal, w es el ancho del canal y h la altura del canal. Por ende se evidencia que la resistencia es directamente proporcional a la longitud del canal y la viscosidad del fluido, mientras que es inversamente proporcional a el ancho del canal [6].

#### 2) Difusión de Microfluidos:

Respecto a (Bharat, 2017, p. 492), es el movimiento de particulas de una mayor concentración a una menor hasta que la concentración media en todo el volumen sea la misma.

Se presenta una relación entre la distancia recorrida por una partícula y el tiempo de difusión, mediante la siguiente ecuación:

![SmartSelect_20240916_231050_Adobe Acrobat](https://github.com/user-attachments/assets/6a8aefe7-fa9e-4783-8889-61b87d8ce00d)

Donde d es la distancia recorrida por la partícula, t el tiempo en el que puede recorrer esa distancia y D el coeficiente de difusión de la partícula. Usando la fórmula presentada se puede apreciar como puede llegar a influir la miniaturización de un sistema en el tiempo de difusión de un fluido.


La microfluídica es amplia y los dispositivos relacionados a ella también lo son. En el ámbito educativo y de laboratorio hay ciertos dispositivos escenciales para poder llevar a cabo distintos procesos, ya sean relacionados a la Biología, Física o Química. Uno de los dispositivos mas importantes son las bombas de microfluidos, las cuales tienen la función de suministrar el fluido ya sea de manera continua o controlada, con un caudal preciso o la difusión exacta requerida para determinados procesos como son la preparación de mezclas para el análisis de líquidos.

### Contexto Nacional:


## Diagrama de Ishikawa
![Inexperience of decision makers (1)](https://github.com/user-attachments/assets/1b7dafea-8c6d-4358-9040-48e468b8287a)


## 3. Definicion de la problematica

La alteración del sistema inmunológico debido a inmunodeficiencias representa un reto para el diagnóstico de la Tuberculosis 


## 4. Contexto científico


## 5. Referencia Bibliograficas
[1] “Open Hardware”. SG Buzz. Accedido el 16 de septiembre de 2024. [En línea]. Disponible: https://sg.com.mx/revista/open-hardware

[2] “What is Arduino?” Arduino - Home. Accedido el 16 de septiembre de 2024. [En línea]. Disponible: https://www.arduino.cc/en/Guide/Introduction

[3] “Raspberry Pi: Qué es, para qué sirve y qué podemos hacer”. Profesional Review. Accedido el 16 de septiembre de 2024. [En línea]. Disponible: https://www.profesionalreview.com/2021/07/18/que-es-raspberry-pi/

[4] “Open-source at Prusa Research | Original Prusa 3D printers directly from Josef Prusa”. Prusa3D by Josef Prusa. Accedido el 16 de septiembre de 2024. [En línea]. Disponible: https://www.prusa3d.com/page/open-source-at-prusa-research_236812/

[5] F. Rivas, “Microfluidos: ¿cuánto hay de nuevo?”, RCF, vol. 25, n.º 2B, p. 142-143, 2008.

[6] Bharat, B. (Ed.). (2017). Handbook of Nanotechnology (4a ed.). Springer. https://doi.org/10.1007/978-3-319-49347-3_16



