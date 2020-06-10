# PRÁCTICA DE LABORATORIO N° 2.

# ANÁLISIS DE MALLAS

**Autores:** León Jiphson, Figueroa Erick, Viracucha William.

# 1. PLANTEAMIENTO DEL PROBLEMA

Al analizar cualquier circuito eléctrico podemos encontrar dos elementos fundamentales, un voltaje y una corriente que circulan a través
de él, y son estos mismos elementos que nos permiten analizar un circuito, de esta forma en 1948 Gustav Kirchhoff propone dos leyes, la 
Ley de Corrientes de Kirchhoff (LCK) y la Ley de Voltajes de Kirchhoff (LVK), esta última plantea la siguiente tesis, la suma de las 
caídas de voltaje en una trayectoria cerrada es igual a la suma de las elevaciones de voltaje, sin embargo, cabe recordar que un circuito 
eléctrico elemental cuenta de una fuente y un resistor.

Es evidente que estos postulados no pudieron presentarse sin un medio que nos permita relacionar los elementos presentes en un circuito 
con el voltaje, es por ello, que Kirchhoff basa la LVK en una ley anterior a esta, la Ley de Ohm, la cual, en conclusión, expresa que el 
voltaje es directamente proporcional al producto de la intensidad por la resistencia, V=IR, siendo este el principio fundamental de la 
relación intensidad-tensión, de esta forma podemos analizar a la LVK, en un circuito fundamental obtenemos que efectivamente la LVK se 
cumple, pero, al observar algún circuito eléctrico en algún libro, juguete o equipo, nos damos cuenta que no se presenta un circuito 
fundamental, basados en estas observaciones surge la hipótesis, ¿Hasta qué punto la Ley de Voltaje de Kirchhoff es aplicable a un circuito
eléctrico?.

Para dar respuesta a la interrogante no se precisa de analizar todos los circuitos existentes y obtener la conclusión de que si y/o 
no se cumple la LVK, en este caso utilizaremos un circuito simplificado que ha nuestro parecer cumple con  los requisitos que plantea
la interrogante, el cuál consistirá en tener un circuito con varios caminos cerrados y dos fuentes de voltaje en diferentes partes del 
circuito.

# 2. OBJETIVOS

- Comprobar experimentalmente el análisis de mallas
- Analizar y evaluar la Ley de Voltaje de Kirchhoff en mallas afectadas por dos fuentes de voltaje.

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

- Circuito para el análisis de mallas.

![](https://github.com/leonsteven2/Pr-ctica-N-2/blob/master/img/Diagrama%20del%20Circuito.PNG)

- Circuito para el análisis de mallas replicado en Tinkercad

![](https://github.com/leonsteven2/Pr-ctica-N-2/blob/master/img/Analisis%20de%20mallas.png)

# 5. LISTA DE COMPONENTES

![](https://github.com/leonsteven2/Pr-ctica-N-2/blob/master/img/Materiales.PNG)

# 6. CONCLUSIONES

- Se demuestra la Ley de voltaje de Kirchhoff al analizar, cada malla como un circuito separado, o el circuito entero.
- La Ley de Voltaje de kirchhoff se cumple en mallas por las que circula una corriente, aunque estas no tengan una fuente de voltaje.
- Los resistores que se encuentran en dos mallas, en su linea de corriente van a tener una intensidad igual a la diferencia de las intensidades de las mallas en las que se encuentra, no obstante el valor obtenido da la igualdad establecida por la Ley de Voltaje de Kirchhoff
- La Ley de Voltaje de Kirchhoff es aplicable a circuitos de corriente continua DC que tengan 1 o varias mallas, elementos o fuentes de voltaje.

# 7. RECOMENDACIONES

- Observar que el circuito se encuentre armado de la misma forma que el diagrama, para evitar fallos en las mediciones, sin embargo, aunque se cambien las resistencias se cumplirá la Ley de Voltaje de Kirchhoff

# 8. CRONOGRAMA 

![](https://github.com/leonsteven2/Pr-ctica-N-2/blob/master/img/cronograma-2.PNG)

# 9. BIBLIOGRAFÍA

- http://www.ecorfan.org/bolivia/researchjournals/Tecnologia_e_innovacion/vol4num13/Revista_de_Tecnologia_e_Innovacion_V4_N13_5.pdf
- http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/02_Leyes_de_Voltajes_y_Corrientes_de_Kirchhoffs.pdf

# 10. ANEXOS

- https://github.com/leonsteven2/Pr-ctica-N-2/blob/master/Anexos/C%C3%A1lculos%20Anal%C3%ADticos.pdf
