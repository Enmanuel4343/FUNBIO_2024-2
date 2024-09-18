# 1. Problemática 🧐

## Contexto 

La microfluidica se encarga de aprovechar las propiedades fisicas que proporcionan el uso y control de fluidos en escalas inferiores a la milimétrica [1].

Partiendo de la base de que las fuerzas viscosas son las dominantes en escalas tan pequeñas, actualmente la microfluidica se utiliza para bastantes ambitos de la ciencia, con aplicaciones tanto para la Química, la Física o la Biologia, pero una de las mas importantes y que se enfoca en la pura experimentación de los fenómenos ligados a este mundo, es su aplicación para los laboratorios en un ámbito educativo.

Dispositivos y equipos usados para la microfluidica hay bastantes, para el contexto de laboratorio, hay dispositivos indispensables, dentro de estos están las bombas de jeringa, las cuales a diferencia de su contraparte las bombas peristalticas, son mucho mas frecuentes en este campo debido a su mejor rendimiento para el control de fluidos a microescala [2].

En el contexto peruano, se presenta una necesidad creciente de bombas de jeringa para microfluidos por parte de universidades y si bien hay universidades que a dia de hoy ya tienen laboratorios de microfluidica con sus respectivas bombas de jeringa, la única manera de conseguirlas es mediante la importación de empresas o fundaciones que las fabriquen, el precio rondando usualmente los 4000 euros [3].

El alto costo puedo no resultar conveniente ni rentable para estas instituciones, debido a que si bien son indispensables para el control de los fluidos, en este campo son usualmente pensados para experimentos y procesos rapidos que requieren segundos para poder concluirse.

Cabe considerar que un alto costo tanto por unidad como de mantenimiento, implica una impedancia a su masificación, puesto que para las universidades, instituciones educativas o investigadores independientes no resulta práctico ni rentable un costo tan alto para experimentos y procesos tan cortos, sin embargo, para el correcto estudio y control de los fluidos a microescalas, estas bombas son indispensables.

Este problema es relevante en el campo de la biomédica principalmente por las distintas aplicaciones que pueden llegar a tener las bombas de jeringa en los laboratorios e investigaciónes, ejemplos claros son los lab-on-a-chip.

## Definición del problema
El problema específico que se está tratando de resolver es el alto costo de adquisición y mantenimiento de las bombas de jeringa para microfluidos en entornos de laboratorio e investigación, particularmente en contextos educativos y en países en desarrollo como Perú. Este problema se ve exacerbado por la necesidad de importar estos dispositivos debido a la falta de fabricantes locales, el costo prohibitivo de los modelos comerciales existentes, y la importancia creciente de la microfluídica en la investigación y educación en ingeniería biomédica[4]. 

Un ejemplo concreto de esta situación en Perú es la adquisición por parte de la UTEC (Universidad de Ingeniería y Tecnología) de la Bomba para microfluidos dual programable Ossila L2003S1, con un precio que ronda los 3600 euros por unidad, lo que ilustra el alto costo que deben afrontar las instituciones educativas para acceder a esta tecnología esencial[5].
## Impacto
El alto costo de las bombas de jeringa para microfluidos tiene un impacto significativo en la educación e investigación en Perú. Según datos del Consejo Nacional de Ciencia, Tecnología e Innovación Tecnológica (CONCYTEC), en 2021 había aproximadamente 3,000 investigadores en ciencias naturales y exactas en Perú [6]. 

Estimando que al menos un 10% de estos podrían beneficiarse de tecnologías microfluídicas, alrededor de 300 investigadores se ven potencialmente afectados. En el ámbito educativo, considerando que Perú tiene más de 140 universidades [7], y asumiendo que al menos 20 de ellas tienen programas relacionados con ingeniería biomédica o ciencias afines, podríamos estar hablando de unos 2,000 estudiantes anualmente que podrían beneficiarse de acceso a esta tecnología (estimando 100 estudiantes por universidad en cursos relevantes). El impacto económico también es considerable: si cada una de estas 20 universidades necesitara adquirir solo una bomba de microfluidos como la mencionada de la UTEC (3,600 euros), el costo total sería de 72,000 euros, equivalente a aproximadamente 300,000 soles peruanos. Este monto representa una inversión significativa para muchas instituciones, especialmente considerando que el presupuesto anual para investigación en muchas universidades peruanas es limitado. Por ejemplo, según un informe de la Superintendencia Nacional de Educación Superior Universitaria (SUNEDU), en 2019, el gasto promedio en investigación por estudiante en universidades públicas fue de solo 1,196 soles anuales [8]. 

Este alto costo limita la capacidad de las instituciones para proporcionar experiencias prácticas esenciales a los estudiantes y restringe las posibilidades de investigación en áreas emergentes como la microfluídica.
# 2. Propuesta de Solución 🤓

## Descripción de la Solución
  Nuestra propuesta busca reducir los costos de fabricación mediante el uso de microcontroladores como Arduino, impresión 3D y motores accesibles en el mercado. De esta manera, pretendemos mejorar el acceso a bombas de jeringa para microfluidos, las cuales suelen tener precios poco accesibles en comparación con las necesidades de los experimentos que requieren resultados rápidos. Además, buscamos aumentar la precisión de estas bombas mediante la incorporación de guías lineales, lo cual es esencial para garantizar la exactitud en los experimentos con microfluidos.
  
## Características del Prototipo
Las características de nuestro dispositivo están orientadas a ser de bajo costo para poder llegar a más instituciones con carencias de instrumentos en sus laboratorios. Será de fácil armado y modificará los rieles laterales comunes por guías lineales para una mayor precisión en el movimiento. Estas guías permiten movimientos muy precisos, lo cual es beneficioso en aplicaciones de microfluidos, donde las variaciones mínimas en el flujo pueden afectar los resultados experimentales.

Además, la fricción ejercida por el pusher block en una guía lineal es más fácil de controlar, lo que facilita la regulación de la velocidad del émbolo de la jeringa. Esto hace que el sistema sea más duradero, estable y capaz de realizar movimientos rápidos con alta precisión y repetibilidad, mejorando así la productividad.

A diferencia de los husillos, que requieren un mantenimiento más constante, nuestro dispositivo será de código abierto para que cualquier persona pueda mejorarlo o reemplazar piezas sin necesidad de adquirir un nuevo dispositivo. La combinación de los principios del husillo y la guía lineal proporciona un control preciso del movimiento y la cantidad de líquido inyectado, mientras que la guía lineal asegura un movimiento suave y estable, evitando desalineaciones y reduciendo la necesidad de mantenimiento frecuente.
## Beneficios
### Guías lineales
-Bajo costo: El dispositivo está diseñado para ser accesible para instituciones con recursos limitados.

-Fácil armado y modulación: simplicidad en su ensamblaje y la posibilidad de modificar componentes.

-Mayor precisión: Las guías lineales mejoran significativamente la precisión del movimiento, lo que es esencial en experimentos de microfluidos.

-Baja fricción: El uso de guías lineales permite un control más preciso sobre la fricción.

-Durabilidad y estabilidad: El sistema es más duradero y estable, con la capacidad de realizar movimientos rápidos y precisos, mejorando la productividad.

-Menor necesidad de mantenimiento: En comparación con los husillos, que requieren mantenimiento constante, la guía lineal ofrece un movimiento suave y estable, reduciendo la necesidad de ajustes frecuentes.

## Viabilidad Técnica
Por viabilidad técnica, se optará por usar guías lineales junto con un husillo y su tuerca correspondiente. Un riel paralelo a la guía lineal se conectará al husillo, que a su vez estará unido a un motor paso a paso. Este motor será el encargado de dar las órdenes de rotación para el desplazamiento del husillo mediante un acoplador flexible. El pusher block se ubicará en la parte de empuje de la jeringa, y el soporte para la jeringa se puede fabricar mediante impresión 3D o corte láser de un material robusto. Un Arduino se utilizará para controlar el motor paso a paso con su código correspondiente.

### Tabla de Componentes

| **Producto**            | **Precio**    | **Especificaciones**                                         |
|-------------------------|---------------|---------------------------------------------------------------|
| Motor paso a paso       | 20 $ aprox    | El motor se usará para convertir el movimiento circular en lineal. |
| Husillo                 | 15 $ aprox    | El husillo debe tener al menos el tamaño de la jeringa.     |          
| Acoplador flexible       | 10 $ aprox    | Conectará el husillo al eje del motor paso a paso.           |          
| Pusher block            | Impresión 3D| Encargado de empujar el émbolo de la jeringa.                |          
| Soporte                 | Impresión 3D| Se utilizarán recursos para impresión 3D.                    |          
| Arduino                 | 40 $          | Controlará el motor paso a paso mediante código.             |         
| Fuente de alimentación  | 10 $          | Necesaria para proporcionar un voltaje de 12V al motor.      |          
| Controlador del motor   | 5 $           | Se usará un DRV8825 o A4988 para configurar el micro-paso, importante en microfluidos. |          
| Patin de guias linelaes | 30$          | Los patines iran en las guiaas lineales se moveran junto con la jeringa||
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
La propuesta del proyecto busca desarrollar una bomba de jeringa casera y de bajo costo utilizando tecnologías accesibles como microcontroladores (Arduino), impresión 3D y motores de mercado. Este prototipo incluirá guías lineales para mejorar la precisión, con el objetivo de reducir los costos sin sacrificar funcionalidad. Se enfoca en aplicaciones experimentales rápidas en microfluidos, especialmente en el campo de la biomedicina.

# 5. Referencias Bibliográficas
[1] F. Rivas, “Microfluidos: ¿cuánto hay de nuevo?”, RCF, vol. 25, n.º 2B, p. 142-143, 2008.

[2] Chang Kyu, B., & Kameel, A.-S. (2024). ELECTROPHORESIS. Wiley Analytical Science, 45(15-16), 1275. https://doi.org/10.1002/elps.201300205

[3] “Laboratory Programmable Syringe Pump - LSPone”. Advanced Microfluidics. Accedido el 17 de septiembre de 2024. [En línea]. Disponible: https://amf.ch/product/lspone-laboratory-syringe-pump/

[4] “Low-cost feedback-controlled syringe pressure pumps for microfluidics applications”. PubMed Central (PMC). Accedido el 18 de septiembre de 2024. [En línea]. 
Disponible: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5378403/#pone.0175089.ref012

[5] Ossila Syringe Pump User Manual. (s.f.). Ossila. https://www.ossila.com/pages/syringe-pump-user-manual
