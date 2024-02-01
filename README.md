[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ke8zCzPd)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=13627298)
# Práctica 4: Algoritmos de ordenamiento
UNIVERSIDAD AUTONOMA METROPOLITANA

Jueves 31 de enero del 2024

Alumna: Estefany Harisvet Sánchez Ortiz

Matricula: 2213028278

Profesor: Abel García Nájera

Materia: Estructura de Datos Lineales

-------------------------------------
 # :dart: Objetivo 

Verificar de forma experimental el tiempo de ejecución de algunos algoritmos de ordenamiento.

#  :nerd_face: Resultados obtenidos y su análisis  

El análisis del problema se centra en la evaluación empírica de algoritmos de ordenamiento, proporcionando información valiosa sobre su rendimiento en diferentes situaciones. La experimentación y el análisis de resultados permitirán entender mejor la eficiencia de estos algoritmos y tomar decisiones informadas sobre su aplicación en distintos contextos.

Se presentan los resultados de tiempo de ejecución (en segundos) para diferentes tamaños de entrada (n) y los algoritmos de ordenamiento: Insertion Sort (IS), Selection Sort (SS), Bubble Sort (BS), Merge Sort (MS) y Quick Sort (QS). A continuación, se realiza un análisis detallado de los datos proporcionados:

## Tabla de resultados y graficas de comparación 

 ![image](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Arisanchez03/assets/125591740/2d0da1a5-8326-4ed0-8ad0-05da3cdec45f)

 ### Insertion Sort (IS): 
- El tiempo de ejecución de Insertion Sort muestra una clara tendencia de aumento a medida que el tamaño de entrada (n) crece.
- Para tamaños de entrada pequeños, IS es extremadamente eficiente, pero su desempeño degrada significativamente para conjuntos más grandes, alcanzando un tiempo considerable para n=10^9.
- La complejidad cuadrática de IS (O(n^2)) se evidencia en su rendimiento.

### Selection Sort (SS): 
- SS también muestra una clara tendencia de aumento en el tiempo de ejecución a medida que n crece.
- Al igual que IS, SS tiene un desempeño muy eficiente para conjuntos pequeños, pero se vuelve impracticable para tamaños grandes.
- La complejidad cuadrática de SS (O(n^2)) es evidente en sus resultados.

### Bubble sort (BS) : 
- BS sigue la misma tendencia que IS y SS, con un rendimiento eficiente para n pequeños y un incremento drástico para tamaños mayores.
- La complejidad cuadrática de BS (O(n^2)) se refleja en sus resultados, siendo especialmente evidente para tamaños mayores.

### Merge Sort (MS):
- MS muestra un rendimiento más constante y eficiente a medida que n aumenta.
- Su complejidad logarítmica (O(n log n)) se refleja en tiempos de ejecución consistentemente bajos, incluso para tamaños de entrada más grandes.
- MS destaca como una opción eficiente para conjuntos de datos considerables.

### Quick Sort (QS):
- QS muestra una eficiencia destacada, incluso para tamaños de entrada más grandes.
- Su complejidad promedio y peor caso (O(n log n)) se traduce en tiempos de ejecución consistentemente bajos.
- QS se destaca como un algoritmo eficiente y confiable en diferentes escenarios.

El análisis general revela que los algoritmos cuadráticos (IS, SS, BS) presentan limitaciones significativas a medida que n crece, volviéndose ineficaces para conjuntos de datos extensos. Por otro lado, los algoritmos de complejidad O(n log n) (MS, QS) destacan por su eficiencia y son preferibles en escenarios que involucran grandes volúmenes de datos.

En última instancia, la elección del algoritmo de ordenamiento debe basarse en una evaluación cuidadosa de los requisitos específicos del conjunto de datos y las características del entorno de aplicación

esto se puede ver representado en la siguiente grafica de promedios: 
 ![image](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Arisanchez03/assets/125591740/d0d5307f-52d2-4cee-ac70-dc5941eaa879)
 
En la siguiente grafica de desviación estandar se puede observar que.. 
- IS muestra desviaciones estándar relativamente pequeñas, indicando consistencia en su rendimiento. Aunque cuadrático, mantiene estabilidad en diversas instancias de conjuntos de datos.
- SS exhibe desviaciones estándar notables, especialmente en conjuntos de datos más grandes. Esto sugiere variabilidad en sus tiempos de ejecución, posiblemente relacionada con su complejidad cuadrática y sensibilidad a la disposición inicial de los datos.
- BS presenta desviaciones estándar significativas, indicando mayor variabilidad en sus tiempos de ejecución. Esto sugiere una sensibilidad a la disposición de los datos, siendo una característica importante a considerar.

En resumen, la desviación estándar ofrece una perspectiva sobre la consistencia y variabilidad de los algoritmos. La estabilidad de IS contrasta con la variabilidad de SS y la sensibilidad de BS, aspectos importantes al seleccionar un algoritmo según los requisitos específicos de la aplicación y la naturaleza del conjunto de datos.
![image](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-Arisanchez03/assets/125591740/d5df1502-3c49-46fe-8d00-b37067f181a2)

# :thought_balloon: Conclusiones 

Con este trabajo podemos concluir diversas cosas, entre las cuales destacan...

1. Ineficiencia de Algoritmos Cuadráticos:

    La complejidad cuadrática de los algoritmos cuadráticos se evidencia en los tiempos de ejecución, haciendo que estos algoritmos sean impracticables para conjuntos de datos extensos (n=10^9).

2. Eficiencia de Algoritmos O(n log n):

    Tanto Merge Sort como Quick Sort, con complejidades O(n log n), demuestran un rendimiento consistente y eficiente incluso para tamaños de entrada considerables. Quick Sort, en particular, destaca como un algoritmo eficiente y confiable.

Por lo tanto, el análisis de los algoritmos de ordenamiento destaca la influencia directa de la complejidad algorítmica en su rendimiento. Algoritmos cuadráticos son eficientes para conjuntos pequeños, pero su eficacia disminuye rápidamente con el aumento del tamaño del conjunto de datos. En contraste, algoritmos de complejidad O(n log n) como Merge Sort y Quick Sort ofrecen eficiencia y consistencia, siendo opciones sólidas para aplicaciones prácticas y sistemas de procesamiento de datos. La elección consciente del algoritmo es esencial para optimizar el rendimiento en función de las necesidades específicas del problema y el tamaño del conjunto de datos.
