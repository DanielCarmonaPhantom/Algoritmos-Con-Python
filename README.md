# Algoritmos con Python


Contenido:

1. Bubble Sort
2. Quick Sort



## Bubble Sort

Es el primer algoritmo de ordenamiento que estaremos viendo, ya que este nos da inicio a la forma en que se mejoraron los demas algortimos. 

Lo que hace es que recorre todo el arreglo evaluando si el elemento de lado izquierdo es mayor al elemento del lado derecho y así hasta llegar a los 2 ultimos elementos.

Al ir moviendo el elemento más grande a la derecha, esto hara que al final quede el elemento más grande de todo el arreglo, ahora tiene que volver a hacerse otro recorrido donde vuelva a evaluar 2 elementos para poder llevarse el segundo elemento menos grande hasta final. 

Como notaras, este arreglo se repite muchas veces hasta que al final ya tenemos el arreglo ordenado de menor a mayor.

Esto quiere decir en terminos de programación que haras un ciclo que pase por todos los elementos y luego otro ciclo que sera el que evalue el elemento de la izquierda y derecha y este pase por todos los elementos donde **no** esta el mayor al final.
