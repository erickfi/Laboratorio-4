# PRÁCTICA DE LABORATORIO N° 4.

# TEOREMA DE SUPERPOSICIÓN.

**Autores:** León Jiphson, Figueroa Erick, Viracucha William.

# 1. PLANTEAMIENTO DEL PROBLEMA

La tensión y la intensidad son elementos fundamentales que un circuito requiere para su funcionamiento, al analizar un circuito estos elementos no solo representan el punto y la dirección por el que circula la corriente, sino que, el voltaje del resto de los elementos electrónicos se verá afectado por el valor de los mismos, al usar las Leyes de Kirchhoff podemos crear relaciones tensión-intensidad, a esto le añadimos la Ley de Ohm que nos permite relacionar los elementos del circuito con los voltajes que tendrán o las corrientes que circulan por sus lazos.

Para analizar un circuito usando las relaciones mencionadas anteriormente, existen dos métodos conocidos, "análisis por mallas o análisis por nodos, cuya aplicación resulta fácil cuando un circuito posee pocos elementos y varias fuentes ya sea de voltaje o corriente"[1], sin embargo, si este número aumenta la dificultad de resolver usando estos métodos será directamente proporcional a este crecimiento, esto no se debe a que los métodos tenderán a fallar a medida que el circuito crece, el error radica en la matemática de la persona que analiza el circuito, de esta forma "surgen métodos alternativos que nos permiten reducir de tamaño el circuito a analizar, como por ejemplo el divisor de corriente o voltaje, la transformación de fuentes, etc" [2].

Aunque los métodos mencionados funcionan aún existe el riesgo de un fallo en el análisis matemático, después de todo seguimos teniendo varias fuentes de corriente y/o voltaje cuyo método de resolución se reduce a un sistema de ecuaciones, de esta forma surgen las interrogantes, ¿Cuál es la probabilidad de que una persona falle en el análisis matemático?, ¿En qué condiciones el análisis usando las Leyes de Kirchhoff, la Ley de Ohm y los divisores de corriente y/o voltaje presentarían resultados aunque aproximados, erróneos?, pero sin lugar a dudas la interrogante más importante es ¿Hasta que punto es necesario la implementación de un nuevo método de análisis de circuitos?

Las dos primeras preguntas planteadas aunque validas su respuesta va a diferir, ya que dependerá de la persona que analice el circuito, a esto se suma que el porcentaje de error de los resultados no radica en los métodos, o las leyes, sino en la persona que usa los métodos de análisis, de esta forma surge el análisis mediante el teorema de superposición, aunque no nos permite reducir los componentes eléctricos que un circuito, si nos permite reducir las fuentes de corriente y/o voltaje, al realizar un análisis individual de como afecta cada fuente al circuito en general.



# 2. OBJETIVOS
**Objetivo General**
- Comprobar experimentalmente el teorema de superposicipon 

**Objetivos específicos**
- Analizar e identificar la interacción de los elementos de un circuito con cada una de las fuentes de voltaje y corriente.
- Calcular y contrastar los voltajes de los elementos de un circuito eléctrico de usando el teorema de superposición y los obtenidos con un multímetro

# 3. MARCO TEÓRICO

El principio o teorema de superposición establece que "la tensión entre los extremos de un elemento en un circuito lineal es la suma algebraica de las tensiones y/o intensidades a través de ese elemento debido a que cada fuente independiente actúa sola"[3].

Un circuito al ser alimentado por una fuente de voltaje o corriente, establece un camino por el que circulará la corriente a través del circuito hasta volver a la fuente, al aumentar el número de fuentes el concepto se sigue cumpliendo para cada una de ellas, y cada una de ellas estimula a cada elemento del circuito, por ello si analizamos fuentes de voltaje o corriente cuya sentido es opuesto, podemos reducir a una sola fuente en una dirección al realizar una suma algebraica de las mismas, y ya que cada una de ellas estimula de forma diferente a cada elemento del circuito se puede calcular el voltaje final al analizar cada uno de los estímulos de las fuentes y realizar una suma algebraica considerando los sentidos de circulación, para realizar este análisis se sigue el siguiente proceso.

**1.**	Apague todas las fuentes independientes, excepto una. Determine la salida de tensión o corriente de la fuente activa aplicando el análisis con las Leyes de Kirchhoff.

**2.**	Repita el paso anterior, para cada una de las demás fuentes independientes.

**3.**	Halle los valores de voltaje o corriente total sumando algebraicamente las obtenidas en los pasos anteriores.

# 4. DIAGRAMAS

- Circuito para el análisis del teorema de superposición

![](https://github.com/erickfi/Laboratorio-4/blob/master/img/diagrama-4.PNG)

- Tensión y corriente del circuito 

![](https://github.com/erickfi/Laboratorio-4/blob/master/img/Thinker%204.1.png)

- Análisis de la primera fuente

![](https://github.com/erickfi/Laboratorio-4/blob/master/img/Thinker%204.2.png)

- Análisis de la segunda fuente

![](https://github.com/erickfi/Laboratorio-4/blob/master/img/thinker%204.3.png)

# 5. LISTA DE COMPONENTES

![](https://github.com/erickfi/Laboratorio-4/blob/master/img/materiales-4.PNG)

# 6. TABLA DE RESULTADOS

- Medición de voltaje aplicando superposición

![](https://github.com/erickfi/Laboratorio-4/blob/master/img/Tabla%20de%20voltajes.PNG)

- Medición de corriente aplicando superposición

![](https://github.com/erickfi/Laboratorio-4/blob/master/img/Tabla%20corrientes.PNG)

# 7. CONCLUSIONES
- Existe un error menor al 1% en los cálculos de voltaje y un 0% en el cálculo de la corriente con el teorema de superposición, por lo tanto, se demuestra que el análisis de superposición funciona.
- Los elementos eléctricos, independientemente de su ubicación en el circuito, son estimulados por cada fuente del circuito.
- Se comprueba el teorema de superposición para voltajes  dado que si se suma la tensión al analizar la primera fuente que es  7.48  V y el voltaje del análisis de la segunda fuente -6.53 V se obtiene el  valor cercano al voltaje final de 952 mV
- Cuando se iguala la fuente de 12V a 0, la corriente que pasa por la resistencia de 470 ohmios es igual 0 ya que en este caso la corriente busca el camino mas facil o con menos resistencia para poder circular.
- Cuando se apaga la fuente de voltaje V2, la corriente Ix es 0, esto se debe a que la corriente tiende a ir por el camino que presenta menor oposición, en este caso la corriente de la fuente V1, se va por el lazo de la resistencia de 2.2 kOhm.

# 8. RECOMENDACIONES

- Para realizar la práctica es necesario aprender a manejar correctamente el multímetro al momento de obtener las corrientes y revisando en que unidades se están manejando
- Cuando se realice los cálculos analíticos es muy importante trabajar con varias cifras significativas, ya que estas influyen mucho en el resultado final.
- El teorema de la Superposición nos va a ayudar a encontrar el voltaje o corriente de cualquier elemento del circuito siempre y cuando apliquemos de forma correcta todos los conceptos. 
- Si aplicamos el teorema de Superposición es necesario tener en cuenta que las fuentes de voltaje al igualarlas a 0 se comportan como un cortocircuito, por otro lado si tuvieramos fuentes de corriente estas se van a comportar como circuitos abiertos.


# 9. CRONOGRAMA 

![](img/cronograma-practica-4.PNG)

# 10. REFERENCIAS

[1] R. B. Bardia.CIRCUITOS Y DISPOSITIVOS ELECTRÓNICOS. FUNDAMENTOSDE ELECTRÓNICA (PT), volume 5. Univ. Politèc. de Catalunya, 1999.

[2] T. F. J. Luis. Presentación sobre: Linealidad y superposición.

[3] M. A. Sadiku.Fundamentos de circuitos eléctricos. Mc Graw Hill, third edition, 2006

# 11. ANEXOS
**- Cálculos Analíticos**

Ver cálculos analíticos < https://github.com/erickfi/Laboratorio-4/blob/master/Anexos/Anexos.pdf >

**- Videos**

Ver video 1 < https://youtu.be/bk-6Zlexov8 >

Ver video 2 < https://youtu.be/n0cYCrd0mjk >
