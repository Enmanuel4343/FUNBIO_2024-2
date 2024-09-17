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

 ## 2. Análasis de la temática:

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

Se presentan una gran variedad de bombas para microfluidos actualmente, según (Chang Kyu & Kameel, 2024, p. 247-249) se tienen 3 tipos de bombas principales:

- Bombas de jeringas:
  
Las bombas mecánicas activas, como las de jeringa y de vacío, permiten un control preciso del flujo de líquidos. Las bombas de jeringa usan un pistón para empujar líquidos, pero están limitadas a volúmenes fijos. Las bombas de vacío crean presión negativa para aspirar líquidos y pueden manejar grandes volúmenes si se mantiene el suministro continuo. Aunque ambas tienen un costo inicial alto y requisitos operativos elevados, existen opciones avanzadas como el sistema de control de flujo microfluídico de Fluigent, que ofrece un control preciso y flexible para aplicaciones más complejas.
- Bombas peristalticas:

Las bombas peristálticas utilizan un tubo flexible presionado por rodillos en un rotor para desplazar líquidos. Ofrecen flujo bidireccional y pueden ser configuradas en formatos abiertos o cerrados. Son menos propensas a la contaminación ya que no tocan el líquido directamente, pero pueden dañar células y sus componentes se desgastan con el tiempo. Aunque las versiones miniaturizadas existen para aplicaciones pequeñas, las bombas peristálticas tradicionales suelen ser voluminosas. Se han desarrollado alternativas compactas, como los pines Braille controlados por computadora, para aplicaciones microfluídicas.
- Bombas electrocinéticas y electroosmóticas:

Las bombas electrocinéticas o electroosmóticas usan electricidad para mover líquidos mediante un campo eléctrico. Generan un flujo tipo "tapón" en lugar de un flujo parabólico y tienen una estructura simple sin partes móviles. Son sistemas "abiertos" que permiten rellenar líquidos en la entrada. Aunque útiles para la entrega de células, deben operar con campos eléctricos bajos para evitar daños celulares y tienen limitaciones por electrólisis. Usar geles o membranas para aislar los electrodos puede superar algunas de estas limitaciones.

Nuestro equipo opto por elegir como objeto de estudio y mejora a las bombas de jeringa para microfluidos, en principio debido a que estas son mejores a la hora de suministrar fluidos teniendo mayor precision a escalas tan pequenas y tambien por su tamano mas manejable.

### Contexto Nacional:

Cuando se habla de bombas de jeringa para microfluidos no muchos se familiarizan, pero en el ámbito educativo y de laboratorio son bastante usadas para bastantes procesos como:

- Dispensación de solución
- Mezcla de soluciones
- Emulsificación
- Recubrimientos dosificados
- Enfriamiento de la solución
- Electrohilado
- Electropulverización
- Microfluídica
- Química del flujo

La UTEC, La Universidad de Ingenieria y Tecnologia, tiene un laboratorio de Microfluidos para el cual adquirieron la Bomba para microfluidos dual programable Ossila L2003S1, con un precio que ronda los 3600 euros por unidad. Esta bomba de jeringa presenta un motor paso a paso, un microprocesador con micropasos de 1/64, 2 jeringas con un tamano minimo de 0.5 microlitros y con las siguientes dimensiones: 330 mm  de ancho, 140 mm de altura y 260 mm de profundidad [8].

Ademas, en Peru hay una gran cantidad de empresas dedicadas a la fabricacion de bombas para el control de fluidos, pero no se logro encontrar empresas que fabricaran bombas de jeringa para microfluidos, en cambio para el caso de las bombas peristalticas, hay empresas como Omega Peru S.A que las fabrican. 

En suma se puede evidenciar mediante un rapido chequeo del contexto peruano, que si bien en el ambito educativo y de laboratorios son requeridas (y se proyecta que mucho mas en un futuro), la unica opcion para poder conseguir estos productos es mediante la importacion, debido a que en Peru no hay empresas dedicadas a la fabricacion de las mismas.

### Contexto Mundial:

En el ámbito mundial, la fabricación de bombas de jeringa para microfluidos y su necesidad para un contexto educativo y de laboratorio presenta un mayor alcance y hay una gran cantidad de empresas dedicadas a su fabricación.

En 2012 se inauguro el laboratorio de microfluidica en la Universidad de Chile, con el fin de poder estudiar los fluidos en escalas muy pequeñas, al interior de redes de microcanales que llegan a tener el grosor de un cabello humano, explica la profesora del departamento de Física de la Facultad de Ciencias Físicas y Matemáticas [9].

Advanced Microfluidics es una fundación Sueca fundada en 2014, dedicada a la fabricación de sistemas y componentes microfluidicos industriales y para laboratorio. Dentro de sus productos presenta una bomba de jeringa programable para laboratorio llamado LSPone, un sistema de dosificación de alta precisión diseñado como un dispositivo de sobremesa para aplicaciones de investigación académica de microfluidos automatizadas [10]. Si bien es un equipo calificado y muy bien implementado, presenta un costo por unidad que ronda los 4700 euros.

## 3. Diagrama de Ishikawa

![SmartSelect_20240917_160911_Canva](https://github.com/user-attachments/assets/4717c40a-32be-45fe-b4a9-eb69e3fe9aa1)

## 4. Definición de la problemática

La alteración del sistema inmunológico debido a inmunodeficiencias representa un reto para el diagnóstico de la Tuberculosis 


## 5. Contexto científico
### 5.1 Low-cost feedback-controlled syringe pressure pumps for microfluidics application
Bomba de presión de jeringa compuesta por cuatro componente: la bomba de jeringa, sensor de presión y amplificador, microcontrolador y controlador del motor. El objetivo es obtener una bomba de bajo costo, con un control sensible y estable para diversos experimentos en chips microfluídicos [9].

![imagen_2024-09-17_154823714](https://github.com/user-attachments/assets/a250558a-fe00-449a-8ccd-fc18d300813b)


### 5.2 


## 6. Referencia Bibliograficas
[1] “Open Hardware”. SG Buzz. Accedido el 16 de septiembre de 2024. [En línea]. Disponible: https://sg.com.mx/revista/open-hardware

[2] “What is Arduino?” Arduino - Home. Accedido el 16 de septiembre de 2024. [En línea]. Disponible: https://www.arduino.cc/en/Guide/Introduction

[3] “Raspberry Pi: Qué es, para qué sirve y qué podemos hacer”. Profesional Review. Accedido el 16 de septiembre de 2024. [En línea]. Disponible: https://www.profesionalreview.com/2021/07/18/que-es-raspberry-pi/

[4] “Open-source at Prusa Research | Original Prusa 3D printers directly from Josef Prusa”. Prusa3D by Josef Prusa. Accedido el 16 de septiembre de 2024. [En línea]. Disponible: https://www.prusa3d.com/page/open-source-at-prusa-research_236812/

[5] F. Rivas, “Microfluidos: ¿cuánto hay de nuevo?”, RCF, vol. 25, n.º 2B, p. 142-143, 2008.

[6] Bharat, B. (Ed.). (2017). Handbook of Nanotechnology (4a ed.). Springer. https://doi.org/10.1007/978-3-319-49347-3_16

[7] Chang Kyu, B., & Kameel, A.-S. (2024). ELECTROPHORESIS. Wiley Analytical Science, 45(15-16), 1275. https://doi.org/10.1002/elps.201300205

[8] Ossila Syringe Pump User Manual. (s.f.). Ossila. https://www.ossila.com/pages/syringe-pump-user-manual

[9] J. R. Lake, K. C. Heyde, and W. C. Ruder, "Low-cost feedback-controlled syringe pressure pumps for microfluidics applications," PLOS ONE 12(4), April 2017. https://doi.org/10.1371/journal.pone.0175089


