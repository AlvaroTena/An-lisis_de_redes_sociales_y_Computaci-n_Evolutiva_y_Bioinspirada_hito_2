# Análisis de redes sociales y Computación Evolutiva y Bioinspirada hito 2

## Introducción
En esta práctica detectaremos comunidades en grafos usando algoritmos evolutivos
multiobjetivo. Se trabajará con una red con datos reales de Amazon. En dicha red cada nodo es
un articulo de Amazon y dos nodos están conectados entre sí cuando suficientes usuarios han
comprado los dos articulos juntos. La red cuenta con una estructura de comunidad conocida, en
concreto, se conoce la categoría de cada producto que será usada como comunidad. La
comunidad a la que pertenece cada nodo está almacenada en el atributo “community” dentro
de cada nodo. Respecto al algoritmo, cada grupo trabajará en base al algoritmo genético
desarrollado en el hito 1.
A menudo al trabajar con datos reales, las comunidades de la red no son equilibradas. Aquí el
número de nodos en cada comunidad:
| **Comunidad** 	| **Número de nodos** 	|
|---------------	|---------------------	|
| 4             	| 327                 	|
| 1             	| 42                  	|
| 0             	| 35                  	|
| 2             	| 24                  	|
| 6             	| 16                  	|
| 5             	| 14                  	|
| 7             	| 9                   	|
| 3             	| 8                   	|

## Objetivos
El objetivo de este ejercicio es doble, por un lado, estudiaremos las limitaciones de la
Modularidad a la hora de detectar comunidades con tamaños muy desbalanceados; por otro
lado, estudiaremos la capacidad de los algoritmos multiobjetivo para analizar una red en
distintos niveles jerárquicos. 