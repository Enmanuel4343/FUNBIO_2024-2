# 1. Problemática 🧐

## Contexto 

La microfluidica se encarga de aprovechar las propiedades fisicas que proporcionan el uso y control de fluidos en escalas inferiores a la milimétrica. 

Partiendo de la base de que las fuerzas viscosas son las dominantes en escalas tan pequeñas, actualmente la microfluidica se utiliza para bastantes ambitos de la ciencia, con aplicaciones tanto para la Química, la Física o la Biologia, pero una de las mas importantes y que se enfoca en la pura experimentación de los fenómenos ligados a este mundo, es su aplicación para los laboratorios en un ámbito educativo.

Dispositivos y equipos usados para la microfluidica hay bastantes, para el contexto de laboratorio, hay dispositivos indispensables, dentro de estos están las bombas de jeringa, las cuales a diferencia de su contraparte las bombas peristalticas, son mucho mas frecuentes en este campo debido a su mejor rendimiento para el control de fluidos a microescala.

En el contexto peruano, se presenta una necesidad creciente de bombas de jeringa para microfluidos por parte de universidades y si bien hay universidades que a dia de hoy ya tienen laboratorios de microfluidica con sus respectivas bombas de jeringa, la única manera de conseguirlas es mediante la importación de empresas o fundaciones que las fabriquen, el precio rondando usualmente los 4000 euros. 

El alto costo puedo no resultar conveniente ni rentable para estas instituciones, debido a que si bien son indispensables para el control de los fluidos, en este campo son usualmente pensados para experimentos y procesos rapidos que requieren segundos para poder concluirse.

Cabe considerar que un alto costo tanto por unidad como de mantenimiento, implica una impedancia a su masificación, puesto que para las universidades, instituciones educativas o investigadores independientes no resulta práctico ni rentable un costo tan alto para experimentos y procesos tan cortos, sin embargo, para el correcto estudio y control de los fluidos a microescalas, estas bombas son indispensables.

Este problema es relevante en el campo de la biomédica principalmente por las distintas aplicaciones que pueden llegar a tener las bombas de jeringa en los laboratorios e investigaciónes, ejemplos claros son los lab-on-a-chip.

## Definición del problema
El problema específico que se está tratando de resolver es el alto costo de adquisición y mantenimiento de las bombas de jeringa para microfluidos en entornos de laboratorio e investigación, particularmente en contextos educativos y en países en desarrollo como Perú. Este problema se ve exacerbado por la necesidad de importar estos dispositivos debido a la falta de fabricantes locales, el costo prohibitivo de los modelos comerciales existentes, y la importancia creciente de la microfluídica en la investigación y educación en ingeniería biomédica[1]. 

Un ejemplo concreto de esta situación en Perú es la adquisición por parte de la UTEC (Universidad de Ingeniería y Tecnología) de la Bomba para microfluidos dual programable Ossila L2003S1, con un precio que ronda los 3600 euros por unidad, lo que ilustra el alto costo que deben afrontar las instituciones educativas para acceder a esta tecnología esencial[2].

# 2. Propuesta de Solución 🤓

## Descripción de la Solución
  Nuestra propuesta busca reducir los costos de fabricación mediante el uso de microcontroladores como Arduino, impresión 3D y motores accesibles en el mercado. De esta manera, pretendemos mejorar el acceso a bombas de jeringa para microfluidos, las cuales suelen tener precios poco accesibles en comparación con las necesidades de los experimentos que requieren resultados rápidos. Además, buscamos aumentar la precisión de estas bombas mediante la incorporación de guías lineales, lo cual es esencial para garantizar la exactitud en los experimentos con microfluidos.
  
## Características del Prototipo

## Beneficios
### Guías lineales
 - Mayor manejo y precisión: perfecto para los experimentos con microfluidos
 - Bajo mantenimiento: debido a un baja fricción no require un mantenimiento constante en comparación con las guias de varilla, degaste acelerado
 - Mayor durabilidad: debido a sus materiales de fabricación

## Viabilidad Técnica
Por viabilidad técnica, se optará por usar guías lineales junto con un husillo y su tuerca correspondiente. Un riel paralelo a la guía lineal se conectará al husillo, que a su vez estará unido a un motor paso a paso. Este motor será el encargado de dar las órdenes de rotación para el desplazamiento del husillo mediante un acoplador flexible. El pusher block se ubicará en la parte de empuje de la jeringa, y el soporte para la jeringa se puede fabricar mediante impresión 3D o corte láser de un material robusto. Un Arduino se utilizará para controlar el motor paso a paso con su código correspondiente.

### Tabla de Componentes

| **Producto**            | **Precio**    | **Especificaciones**                                         | **Foto** |
|-------------------------|---------------|---------------------------------------------------------------|----------|
| Motor paso a paso       | 20 $ aprox    | El motor se usará para convertir el movimiento circular en lineal. |          |
| Husillo                 | 15 $ aprox    | El husillo debe tener al menos el tamaño de la jeringa.     |          |
| Acoplador flexible       | 10 $ aprox    | Conectará el husillo al eje del motor paso a paso.           |          |
| Pusher block            | Impresión 3D| Encargado de empujar el émbolo de la jeringa.                |          |
| Soporte                 | Impresión 3D| Se utilizarán recursos para impresión 3D.                    |          |
| Arduino                 | 40 $          | Controlará el motor paso a paso mediante código.             |          |
| Fuente de alimentación  | 10 $          | Necesaria para proporcionar un voltaje de 12V al motor.      |          |
| Controlador del motor   | 5 $           | Se usará un DRV8825 o A4988 para configurar el micro-paso, importante en microfluidos. |          |
# 3. Coherencia 🤫

## Contexto del Proyecto
Para las investigaciones y practicas de laboratorio, se necesitan diferentes componentes (maquinas, sistemas y equipos) para poder realizar experimentos. La mayor parte de estos requieren una fuerte inverción para poder adquirirlas, y en algunos casos no se pueden conseguir estos equipos en nuestro país por lo que se tienen que importar y esto asu vez eleva más el costo. 

En nuestro contexto, la bomba de jeringa es un prototipo con un costo bastante elevado, el cual no es tan facil de adquirir y que podria llegar a ser prototipado de forma casera. Esto ayudaria de gran manera al área de investigacion, ya que en muchos casos se buscan hacer pruebas rapidas que no necesiten de todo un sistema de operaciones para el proceso. Estas bombas pueden ser de gran ayuda en el campo de la ingenieria biomedica ya que se pueden usar para la experimentacion en áreas como la biologia celular, los cultivos celulares, biotecnologia, etc.Y esto gracias al manejo de los microfluidos.  

## Objetivos del Proyecto
Objetivo principal: Usar los conocimientos en el campo de la microfluídica para prototipar una bomba de jeringa cacera.
Objetivos especificos: 
- Ajustar los componentes con las medidas y parametros necesarias para que el prototipo funcione.
- Probar la funcionalidad del prototipo y comprobar si los resultados obtenidos son correctos.

## Justificación del Prototipo
Hay muchos tipos de bombas de microfluidos en el mercado, y todas tienen caracteristicas distintas, lo que hace que se lleguen a usar en diferentes áreas. Sin embargo, para nuestro proyecto se elijio la bomba de jeringa ya que esta es la que nos permite tener un mayor control del flujo de los liquidos a volumenes pequeños. 

Esto las diferencia del resto de bombas que tambien permiten manejar un flujo continuo, pero que no son tan precisas al momento de medir volumenes pequeños como los que se manejan cuando se va a experimentar.  

## Alineación con el Problema
La problemática establecio que los costos por equipo y por mantenimiento del equipo eran muy altos, lo cual en consecuencia para el contexto peruano resulta poco conveniente y no rentable, debido a que sus fines de uso en laboratorio es para experimentos y procesos cortos.

El prototipo presentado busca economizar y reducir los costos de fabricación de las bombas de jeringa enfocadas en el uso de laboratorio, realizando cambios que no compromentan el funcionamiento óptimo de la bomba de jeringa, para así resultar mas accequibles no solo en el ámbito de laboratorio universitario, si no también masificarse a todo tipo de instituciones e investigadores independientes.

Por ende, el prototipo atiende a la problemática y resulve directamente el problema de altos costos.

# 4. Resumen 🤪

# 5. Referencias Bibliográficas
[1] “Low-cost feedback-controlled syringe pressure pumps for microfluidics applications”. PubMed Central (PMC). Accedido el 18 de septiembre de 2024. [En línea]. 
Disponible: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5378403/#pone.0175089.ref012
[2] Ossila Syringe Pump User Manual. (s.f.). Ossila. https://www.ossila.com/pages/syringe-pump-user-manual
