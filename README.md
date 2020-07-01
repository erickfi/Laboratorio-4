# PRÁCTICA DE LABORATORIO N° 4.

# ANÁLISIS DE MALLAS

**Autores:** León Jiphson, Figueroa Erick, Viracucha William.

# 1. PLANTEAMIENTO DEL PROBLEMA

La tensión y la intensidad son elementos fundamentales que un circuito requiere para su funcionamiento, al analizar un circuito estos elementos no solo representan el punto y la dirección por el que circula la corriente, sino que el voltaje del resto de los elementos electrónicos se verá afectado por el valor de los mismos, al usar las Leyes de Kirchhoff podemos crear relaciones tensión-intensidad, a esto le añadimos la Ley de Ohm que nos permite relacionar los elementos del circuito con los voltajes que tendrán o las corrientes que circulan por sus lazos.

Para analizar un circuito usando las relaciones mencionadas anteriormente, existen dos métodos conocidos, análisis por mallas o análisis por nodos, los cuáles resultan efectivos e inmediatos cuando un circuito posee pocos elementos y varias fuentes ya sea de voltaje o corriente, sin embargo, si este número aumenta la dificultad de resolver usando estos métodos será directamente proporcional a este crecimiento, esto no se debe a que los métodos tenderán a fallar a medida que el circuito crece, el error radica en la matemática de la persona que analiza el circuito, de esta forma surgen métodos alternativos que nos permiten reducir de tamaño el circuito a analizar, como por ejemplo el divisor de corriente o voltaje, la transformación de fuentes, etc.

Aunque los métodos mencionados funcionan aún existe el riesgo de un fallo en el análisis matemático, después de todo seguimos teniendo varias fuentes de corriente y/o voltaje cuyo método de resolución se reduce a un sistema de ecuaciones, de esta forma surgen las interrogantes, ¿Cuál es la probabilidad de que una persona falle en el análisis matemático?, ¿En qué condiciones el análisis usando las Leyes de Kirchhoff, la Ley de Ohm y los divisores de corriente y/o voltaje presentarían resultados aunque aproximados, erróneos?, pero sin lugar a dudas la interrogante más importante es ¿Hasta que punto es necesario la implementación de un nuevo método de análisis de circuitos?

Las dos primeras preguntas planteadas aunque validas su respuesta va a diferir, ya que dependerá de la persona que analice el circuito, a esto se suma que el porcentaje de error de los resultados no radica en los métodos, o las leyes, sino en la persona que usa los métodos de análisis, de esta forma surge el análisis mediante el teorema de superposición, aunque no nos permite reducir los componentes eléctricos que un circuito, si nos permite reducir las fuentes de corriente y/o voltaje, al realizar un análisis individual de como afecta cada fuente al circuito en general.



# 2. OBJETIVOS

- Comprobar experimentalmente el teorema de superposicipon 
- Analizar e identificar la interacción de los elementos de un circuito con cada una de las fuentes de voltaje y corriente.
- Calcular y contrastar los voltajes de los elementos de un circuito eléctrico de usando el teorema de superposición y los obtenidos con un multimetro

# 3. MARCO TEÓRICO

Las Leyes de Kirchhoff están basadas en dos leyes fundamentales en la ciencia, la Ley de Conservación de la Carga y la Ley de conservación de la Energía, de esta forma Gustav Kirchhoff en 1848 plantea sus leyes entre ellas tenemos a la Ley de Voltaje de Kirchhoff, la cual postula _En un camino cerrada la suma de las subidas de tensión es igual a la suma de las caídas de tensión,_ sin embargo, esta ley se complementa con la Ley de Ohm, teniendo una relación adecuada que relacione la tensión y la intensidad.

Dentro del análisis de circuitos usando la Ley de Voltaje de Kirchhoff se usa el método de nodo de voltaje dentro del cuál podemos encontrar tres tipos diferentes de variaciones o variables.

- Resistencia y fuentes de corriente independiente.
- Resistencia y fuentes de corriente y voltajes independientes.
- Resistencia y fuentes de voltaje dependientes

Al analizar un circuito encontramos que los voltajes llegan a variar dependiendo de la cantidad de elementos presentes en un circuito, de igual forma se encuentra una corriente circulando por una linea que conecta los terminales de los elementos del circuito, esta corriente es utilizada en el análisis de mallas con la Ley de voltajes de Kirchhoff, ya que se recomienda seguir 3 pasos para el análisis del circuito y la obtención de los valores de voltaje y corriente.

- **1.** Identificar las mallas en el circuito.
- **2.** Idealizar la corriente que circula por la malla y el sentido de la misma, se recomienda el sentido positivo para todas las corrientes.
- **3.** Aplicar la Ley de Voltaje de Kirchhoff realizando la sumatoria de las tensiones, usar la ley de Ohm para las relaciones de voltaje-corriente, y realizar el sistema de ecuaciones con las n incógnitas presentadas según el número de mallas.

Por otro lado, existen circuitos que contienen más de una fuente, y mallas que no tienen una fuente pero, que circula una corriente por sus lineas.

# 4. DIAGRAMAS


# 5. LISTA DE COMPONENTES



# 6. CONCLUSIONES


# 7. RECOMENDACIONES



# 8. CRONOGRAMA 

![](img/cronograma-practica-4.PNG)

# 9. BIBLIOGRAFÍA

- http://www.ecorfan.org/bolivia/researchjournals/Tecnologia_e_innovacion/vol4num13/Revista_de_Tecnologia_e_Innovacion_V4_N13_5.pdf
- http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/02_Leyes_de_Voltajes_y_Corrientes_de_Kirchhoffs.pdf

# 10. ANEXOS

- https://github.com/leonsteven2/Pr-ctica-N-2/blob/master/Anexos/C%C3%A1lculos%20Anal%C3%ADticos.pdf
