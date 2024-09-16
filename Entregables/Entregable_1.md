# Introducción
## 1. Definicion de Open Hardware
Open Hardware, o hardware abierto, es cualquier dispositivo o componente cuyo diseño y planos son accesibles para que cualquiera los use, modifique o fabrique. La idea es que, al igual que el software de código abierto, puedas ver cómo funciona, cambiarlo para adaptarlo a tus necesidades, y compartirlo con otros. Esto fomenta la colaboración, la innovación, y hace que el hardware sea más accesible y personalizable.
### Ejemplos Conocidos de Open Hardware
 - Arduino: Placas electrónicas que puedes programar para hacer casi cualquier cosa, desde robots hasta dispositivos de domótica. Sus diseños son abiertos y modificables.
 - Raspberry Pi: Una mini computadora de bajo costo utilizada para aprender a programar, proyectos DIY, y más. No es 100% abierta, pero es muy popular en la comunidad.
 - Prusa i3: Una impresora 3D cuyo diseño es totalmente abierto, permitiendo que cualquiera la modifique o fabrique sus propias versiones.
 - Open Compute Project (OCP): Iniciado por Facebook, abre el diseño de servidores y equipos de centros de datos para hacerlos más eficientes y accesibles.
### ¿Por qué es Importante?
- Personalización: Puedes adaptar el hardware a tus necesidades específicas.
 - Transparencia y seguridad: Puedes revisar y mejorar los diseños.
 - Colaboración e innovación: Más personas pueden contribuir con ideas y mejoras.
 - Ahorro de costos: No necesitas pagar licencias o royalties.

 ## 2. Desarrollo de la tematica:

### Definicion de terminos clave: Lab-on-a-chip, Microfluidos

Nos centramos en el uso de bombas cardiacas de flujo continuo en sistemas de circulación extracorpórea en intervenciones quirúrgicas cardiacas.

La circulación extracorpórea (CEC) es un procedimiento médico que desvía la circulación sanguínea del paciente hacia un sistema externo para oxigenar y mantener el flujo sanguíneo cuando el corazón y los pulmones no pueden realizar sus funciones.
En 1953, se desarrolló la bomba de circulación extracorpórea (BCE) por John Gibbon. Este invento revolucionó la cirugía cardíaca, que hasta entonces solo podía tratar patologías extracardíacas. Antes de la BCE, se utilizaba la hipotermia para reducir el metabolismo del paciente y prolongar el tiempo de paro circulatorio, pero esto era un proceso complicado y arriesgado.
La BCE permitió por primera vez tratar trastornos intracardíacos congénitos o adquiridos con mayor seguridad y eficacia. A lo largo del tiempo, la BCE se ha perfeccionado tanto que actualmente presenta una tasa de complicaciones muy baja en pacientes jóvenes sin otras patologías.
Todo el proceso de conexión de una BCE a el paciente se puede dividir en 8 pasos:
### 1.- Heparinización del sistema:
La anticoagulación es fundamental en la circulación extracorpórea (CEC) para evitar la formación de coágulos que pueden causar embolias graves, especialmente en el cerebro y los riñones. Se administra heparina (2-3 mg/kg) para prevenir la coagulación, generalmente directamente en la aurícula derecha o a través de una vía central. La efectividad de la heparina se controla con el ACTest, buscando un tiempo de coagulación adecuado de 480 segundos. En el pasado, la falta de medición precisa de la heparina provocó hemorragias posoperatorias por una neutralización inadecuada del anticoagulante.
### 2.- Conexión del paciente al sistema extracorpóreo:
En la circulación extracorpórea (CEC), se utiliza un líquido de cebado para llenar el sistema y se eliminan burbujas para evitar embolias. Se administra heparina y se colocan cánulas: una para extraer sangre de la aurícula derecha y otra para devolverla a la aorta. La sangre oscura entra en la BCE por gravedad, mientras que la sangre oxigenada regresa al paciente mediante una bomba. La correcta oxigenación se verifica por el color de la sangre y con pruebas gasométricas.
La BCE también tiene líneas para aspirar sangre, ventear cavidades izquierdas y administrar cardioplejía para detener el corazón. Durante la CEC, el corazón y los pulmones pueden funcionar parcialmente. El tiempo de clampeo comienza cuando se coloca una pinza (clamp) en la aorta y se inyecta cardioplejía, y termina al retirar la pinza.
### 3.- Hemodilución:
Un paciente adulto promedio tiene una volemia de aproximadamente 5 litros. Al agregar hasta 1,2 litros de líquido para cebar el sistema de circulación extracorpórea (CEC), la sangre se diluye. Aunque se pensó en usar sangre para cebar, la viscosidad, el riesgo de coágulos y posibles infecciones llevaron al uso de soluciones cristaloides, que mejoran el flujo sanguíneo y la hemodilución.
Durante la CEC, el flujo es no pulsátil, el hematocrito es bajo (22-24%), la sangre no coagula por la heparina, y la temperatura corporal puede variar. Pacientes anémicos pueden necesitar transfusiones de glóbulos rojos, mientras que aquellos con poliglobulia pueden tener parte de su masa globular extraída y reinfundida después de la CEC. La correcta configuración de los rodillos de la BCE es importante para evitar la destrucción de elementos sanguíneos y hemólisis, que puede causar daño renal. La hematuria post-CEC debe diferenciarse de la hemoglobinuria para determinar su causa.
### 4.- Flujo a suministrar:
Para estimar el requerimiento metabólico, se usa una tabla que combina peso y talla para calcular la superficie corporal. Se considera un flujo óptimo de 2,5 litros por metro cuadrado de superficie corporal, lo que resulta en un flujo habitual de aproximadamente 5 litros por minuto para una superficie promedio de 1,8 metros cuadrados.
En pacientes grandes, se pueden necesitar flujos más altos, lo que podría causar problemas hematológicos y requerir sistemas de BCE especializados, como los centrífugos. El flujo adecuado es el que mantiene al paciente con pH normal y sin acidosis metabólica. Si el paciente presenta acidosis o shock antes de la CEC, debe corregirse durante la fase inicial, ya que la acidosis sostenida puede afectar la contractilidad cardíaca y la coagulación postoperatoria. La concentración de ácido láctico es un buen indicador para monitorear estos problemas.
### 5.- RECUPERACIÓN DE LA SANGRE DERRAMADA EN EL PERICARDIO Y/O CAVIDAD PLEURAL:
Durante la circulación extracorpórea, la sangre vertida en la cavidad pericárdica y pleural se puede recuperar y dirigir al oxigenador gracias a la heparinización y las líneas de aspiración. Sin embargo, antes de administrar heparina y después de neutralizar con protamina, no se puede aspirar sangre, a menos que se use un sistema especial de recuperación llamado cell saver. Este dispositivo recupera y lava glóbulos rojos, no sangre completa, y se utiliza en situaciones de sangrado especial, pero no es comúnmente usado.
### 6.- Temperatura corpórea:
La temperatura en cirugía cardíaca es crucial porque influye en el consumo de oxígeno: cada grado de descenso reduce el consumo en un 5-7%. La hipotermia durante la circulación extracorpórea (CEC) ayuda a preservar los tejidos y otorga tiempo adicional de protección. Aunque en el pasado se usaba rutinariamente, hoy se prefiere la normotermia por las posibles complicaciones de la hipotermia, como problemas en la coagulación y función pulmonar.
Durante la CEC, la temperatura del paciente desciende naturalmente debido a la anestesia y el contacto con tubuladuras frías, y se controla con un intercambiador de calor. La hipotermia profunda (menor de 20°C) permite tiempos de isquemia de hasta 45 minutos, pero puede alargar el tiempo quirúrgico y se usa principalmente en casos como disección aórtica y aneurisma del cayado aórtico.
### 7.- Proteccion miocardiaca:
Se basa en el hecho de que diferentes tejidos tienen distintos niveles de tolerancia a la isquemia. El músculo cardíaco, por ejemplo, no soporta más de 30 minutos sin circulación. La protección del miocardio es crucial debido a que la oclusión de la aorta durante la cirugía afecta la circulación coronaria. Se emplean varias estrategias:
-	Clamp intermitente: El clamp se coloca y se retira periódicamente para permitir la reperfusión de las coronarias, con un máximo de 30 minutos de oclusión y 5 minutos de reperfusión. Esta técnica se utiliza menos hoy en día.
-	Clamp permanente: Se usa cardioplejía para proteger el miocardio, inyectando soluciones ricas en potasio a bajas temperaturas para inducir un paro cardíaco controlado. Las soluciones pueden ser cristaloides o sanguíneas, administradas por vía anterógrada o retrógrada.
-	Sin clamp, con BCE: En algunas técnicas, como cirugía tricuspídea o reparación de una rotura cardíaca, se mantiene la perfusión coronaria mientras el corazón sigue latiendo con el apoyo de la BCE.
-	Sin clamp ni BCE: En casos como bypass coronario sin CEC, el corazón late por sí solo. Se puede usar un shunt para mantener el flujo durante el tiempo de isquemia y se emplea dióxido de carbono para limpiar el exceso de sangre en la anastomosis.
### 8.- DESCONEXIÓN DEL SISTEMA Y NEUTRALIZACIÓN DE LA ANTICOAGULACIÓN:
El proceso post-circulación extracorpórea (CEC) incluye:
-	Retiro del clamp aórtico: Se retira mientras el paciente está perfundido por la BCE, con el corazón y pulmones detenidos. El corazón puede comenzar a latir o presentar fibrilación ventricular. En caso de fibrilación, se realiza desfibrilación eléctrica directamente en el corazón.
-	Monitoreo y ajuste: Con el corazón asistido por la BCE, se ajusta el caudal de la CEC. Cuando el corazón mantiene una circulación adecuada, se detiene la BCE.
-	Transición a la función cardíaca natural: El corazón comienza a contraerse por sí mismo, y los pulmones son ventilados mecánicamente. Se retira la línea de la aurícula derecha/cava, devolviendo el volumen residual a través de la cánula aórtica, evitando la sobredistensión del ventrículo derecho.
-	Manejo de heparina y protamina: Se calcula la heparina circulante y se administra protamina para inactivarla. Luego se retira la cánula arterial y se corrige la hemostasia si es necesario.
-	Descarte del equipo: Todo el sistema de CEC se descarta, dejando la BCE de rodillos y el intercambiador listo para el próximo procedimiento. 



## Diagrama de Ishikawa
![Inexperience of decision makers (1)](https://github.com/user-attachments/assets/1b7dafea-8c6d-4358-9040-48e468b8287a)


## 3. Definicion de la problematica

La alteración del sistema inmunológico debido a inmunodeficiencias representa un reto para el diagnóstico de la Tuberculosis 


## 4. Contexto científico
### 4.1.  Artificial Intelligence, Radiology, and Tuberculosis: A Review 
Debido a la alta mortalidad de la tuberculosis en **países en vías desarrollo o donde existe una deficiente atención médica**, se busca cerrar esa brecha mediante el uso de **inteligencia artificial en el diagnóstico de tuberculosis** mediante radiografías de torax desde un **diagnóstico asistido por computadora hasta algoritmos avanzados**. Se muestra como el desarrollo de esta tecnología podría mejorar la calidad vida en un futuro[5].


### 4.2. Factibilidad de una aplicación móvil para el monitoreo de contactos de tuberculosis multidrogorresistente en Perú  
La telemedicina ha jugado un papel crucial en la atención sanitaria en Perú durante la pandemia de COVID-19, proporcionando una solución efectiva para mantener la continuidad del cuidado y facilitar el acceso a servicios médicos a pesar de la infraestructura limitada y la falta de capacitación. Este enfoque ha demostrado ser valioso para superar barreras geográficas y mejorar la eficiencia en la atención, destacando la necesidad de fortalecer la infraestructura tecnológica y el apoyo para optimizar su uso en el futuro.
### 4.3.  Robotic microscopy for everyone: the OpenFlexure microscope
Los microscopios ópticos son de gran importancia en la detección de enfermedades como para los análisis científicos, pero debido a su alto costo su uso es limitado en todo el mundo. Los microscópios OpenFlexure son microscopios de código abierto, impresos en 3D y automatizados. Esta tecnología solventa la necesidad de una fabricación de menor costo y en cantidad.

Joel T. Collins, Joe Knapper, Julian Stirling, Joram Mduda, Catherine Mkindi, Valeriana Mayagaya, Grace A. Mwakajinga, Paul T. Nyakyi, Valerian L. Sanga, Dave Carbery, Leah White, Sara Dale, Zhen Jieh Lim, Jeremy J. Baumberg, Pietro Cicuta, Samuel McDermott, Boyko Vodenicharski, and Richard Bowman, "Robotic microscopy for everyone: the OpenFlexure microscope," Biomed. Opt. Express 11, 2447-2460 (2020)

### 4.4. GeneXpert MTB/RIF
El GeneXpert MTB/RIF se ha convertido en una herramienta crucial para el diagnóstico rápido de la tuberculosis. Este no solo detecta el Mycobacterium tuberculosis, sino que también identifica si hay resistencia a rifampicina, un medicamento clave en el tratamiento. Al ofrecer resultados en menos de dos horas, facilita el inicio rápido del tratamiento, algo especialmente valioso en regiones con recursos limitados. Su uso mejora la precisión en la identificación de cepas resistentes y acelera el proceso diagnóstico, contribuyendo significativamente a una mejor gestión de la tuberculosis en todo el mundo.

Referencia: Zeka, A. N., Tasbakan, S., & Cavusoglu, C. (2011). Evaluation of the GeneXpert MTB/RIF assay for rapid diagnosis of tuberculosis and detection of rifampin resistance in pulmonary and extrapulmonary specimens. Journal of Clinical Microbiology, 49(12), 4138-4141. https://pubmed.ncbi.nlm.nih.gov/21956978/

## Referencia Bibliograficas


[5]Kulkarni, S., & Jha, S. (2020). Artificial Intelligence, Radiology, and Tuberculosis: A Review. Academic radiology, 27(1), 71–75. https://doi.org/10.1016/j.acra.2019.10.003
https://www.scielosp.org/pdf/rcsp/2015.v41n3/532-546/es

[6]M. V. Villarreal, A. Salazar, F. Quispe, M. Reátegui, and J. Martínez, "Percepción de los profesionales de salud sobre la telemedicina en el contexto de la pandemia COVID-19 en Perú," Revista Peruana de Medicina Experimental y Salud Pública, vol. 38, no. 2, pp. 272-277, 2021. [Online]. Available: https://www.scielosp.org/article/rpmesp/2021.v38n2/272-277/. [Accessed: Aug. 27, 2024].
