# Sistemas-Inteligentes e Inteligencia Artificial 
---------------------------------------------------------

Dos de las asignaturas realizadas en la carrera de Ingeniería informática dónde se aprenden las bases de inteligencia artificial aplicadas a distintas prácticas en las cuales se ponen a prueba conocimientos concretos.  


## Sistemas-Inteligentes

Conjunto de proyectos realizados en el segundo semestre del tercer curso de Ingeniería Informática por **Mireya Quintana y Haizea Rodriguez**


### ASS02

**This project is inspired in a problem proposed by Google in its Hash Code 2020's final round:**

We have to define the movements that a robotic arm has to make in order to assemble the components of a mobile phone.

The problem scenario is an MxN grid in which an anchor point for the robot is identified, the assembly points that the robot must visit, and boxes that cannot be crossed (or forbidden).

With each move, the robot extends and occupies the squares it crosses.

### ASS03

The project is inspired by a well-known problem called the **Knapsack** problem.

On the one hand, we have a list of items with a volume and an associated value.

On the other hand, we have a backpack with a maximum capacity.


- Implement the **Random Restart Hill Climbing Method**
- Implement the **Local Beam Search Method**
- Experiment and compare results

### ASS04

#### (1) **How accurately can average, minimum and maximum temperature be predicted from historical data?**

We will analyse the margin of error when predicting the minimum, average and maximum temperature based on historical data.

We will use a CSV available in the Drive folder with data from the AEMET OpenData service (loiu_2000-01_2021-03.csv).

Loiu Airport weather station between 1 January 2010 and 31 March 2021. The dataset has 4018 records of 20 attributes.

#### (2) **Divorce prediction.**

Within this assignment, you will create a decision tree able to predict if a couple will divorce or not depending of answer given to a standard psicological form.

Data from 190 participants (49% divorced and 51% married) is available in the Drive folder. In the folder, you also have an excel file with questions in the form.

## Laboratorio de inteligencia artificial 


### Práctica_01_Fuzzy_Logic

Sistema Basado en Lógica Difusa capaz de dar una valoración entre 0 y 100 de los jugadores de baloncesto a partir de las características del fichero de datos que puede encontrar en el directorio Drive de materiales.

Fuente de los datos: https://www.kaggle.com/jacobbaruch/basketball-players-stats-per-season-49-leagues

Deberá filtrar los datos y quedarse con aquellos de la última temporada, para evitar tener jugadores repetidos.
Es deseable el sistema sea capaz de asignar una valoración cercana a 0 (en el caso del peor jugador), así como cercana a 100 (en el caso del mejor jugador).
También es deseable que no existan muchos jugadores con puntuación similar.

### Práctica_02_Algoritmo_Genético

- Implementar la función Rastrigin como función objetivo (sustituyendo a onemax en el ejemplo dado).
- Definir una función de inicialización que genere un número determinado (n_pop) de individuos de 10 elemenos reales aleatorios en el rango [-5.12, 5,12].
- Definir una función de Selección de Torneo (como la dada en el ejemplo).
- Definir un operador de cruce aritmético que, dados dos individuos, genere dos hijos aleatorios en el rango definido por sus padres.Es decir si un padre tiene, en una posición el valor 3, y el otro el valor -1, ambos hijos tendrán en esa posición un valor aleatorio en el rango [-1,3].
- Los hijos se generarán con una probabilidad r_cross.
- Definir un operador de mutación que, dado un hijo, para cada posición, y con una probabilidad r_mut cambie el valor por un valor aleatorio en el rango de la función.
- Implemente y pruebe la función genetic_algorithm para 1000 iteraciones.


