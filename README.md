

![](/home/alvaro/Escritorio/TFG/GIT/TFG/Memoria/Imágenes/ugr.jpg)

# **Procesos Gaussianos para Aprendizaje Automático Supervisado**

Este repositorio alberga el Trabajo de Fin de Grado (TFG) de Álvaro Luna Ramírez, presentado para la obtención del título del Doble Grado en Matemáticas e Ingeniería Informática por la Universidad de Granada.

## Descripción del Proyecto

Este proyecto estudia en profundidad la formulación teórica de los Procesos Gaussianos e investiga su aplicación en tareas de aprendizaje supervisado, resaltando tanto su eficacia como sus limitaciones. Los Procesos Gaussianos son herramientas que adoptan un enfoque probabilístico, permitiendo el trato de la incertidumbre en las predicciones mediante la inferencia Bayesiana facilitada por el Teorema de Bayes. Sin embargo, un inconveniente significativo es su complejidad computacional, que escala de forma cúbica con el número de muestras de entrenamiento.



En este trabajo, estudiamos modelos avanzados basados en Procesos Gaussianos, enfocándonos en problemas de regresión y clasificación. La tarea de clasificación presenta desafíos debido a la naturaleza no gaussiana de la función de verosimilitud, lo que requiere la adopción de la aproximación de Laplace, que aproxima la posteriori como una distribución normal. Además, investigamos funciones de covarianza esenciales como kernels estacionarios, isotrópicos y basados en el producto escalar, junto con la optimización de hiperparámetros.



La investigación incluye una comparación de Procesos Gaussianos con otros modelos populares en varios conjuntos de datos. Los resultados muestran que, aunque los Procesos Gaussianos logran una alta precisión y permiten una estimación de la incertidumbre, su costo computacional es mayor para aplicaciones con grandes conjuntos de datos, por lo que son menos prácticos en tales escenarios.



Este trabajo amplía conceptos estudiados durante la carrera. Se estudia en detalle un modelo probabilístico que no se ha abordado en la asignatura de ’Aprendizaje Automático’ y se da una nueva perspectiva sobre el manejo de la incertidumbre en esta área. Se profundiza en la ’Inferencia Estadística’ con un enfoque bayesiano, explorando cómo se pueden actualizar las probabilidades utilizando el Teorema de Bayes a medida que se dispone de nueva información. Además, se amplían los conocimientos de ’Estadística Multivariante’ mediante el uso de Procesos Gaussianos, que generalizan los conceptos de la distribución normal a un número infinito de variables aleatorias.



Se muestra en el presente repostiorio el código asociado a  la parte experimental del TFG junto con la memoria.



## Estructura del Repositorio



El repositorio está organizado en varias carpetas:

- **`docs`**: Contiene la bibliografía esencial del TFG.

- **`Memoria`**: Incluye la memoria del TFG, junto a una subcarpeta que contiene todas las imágenes utilizadas.

- **`Gráficos Capítulos 2 3 4 5`**: Incluye 4 subcarpetas:
  
  1. **`Gráficos Capítulo 2`**:  Cuadernos de Google Colab utilizados para las gráficas del Capítulo 2.
  2. **`Gráficos Capítulo 3`**:  Cuadernos de Google Colab utilizados para las gráficas del Capítulo 3.
  3. **`Gráficos Capítulo 4`**:  Cuadernos de Google Colab utilizados para las gráficas del Capítulo 4.
  4. **`Gráficos Capítulo 5`**:  Cuadernos de Google Colab utilizados para las gráficas del Capítulo 5.
  
- **`Experimentos Capítulo 6`**: También contiene 4 subcarpetas:

  1. **`6.1`**:  Contiene el cuaderno de Google Colab utilizado en el experimento visual del apartado 6.1, en el que se comparan un modelo determinista (Regresión Ridge) y otro bayesiano (Procesos Gaussianos).
  2. **`6.2.1`**:   Contiene el cuaderno de Google Colab utilizado en el experimento del apartado 6.2.1, en el que se trabaja un problema de clasificación multiclase: *Optical Recognition of Handwritten Digits*.
  3. **`6.2.2`**:  Contiene el cuaderno de Google Colab utilizado en el experimento del apartado 6.2.2, en el que se trabaja un problema de clasificación multiclase sobre especies de flores Iris.
  4. **`6.3`**:  Contiene el cuaderno de Google Colab utilizado en el experimento del apartado 6.3, en el que se trabaja un problema de regresión sobre niveles de CO2 en el Volcán Mauna Loa (Hawái).
  
  
  
     
## AUTOR
Álvaro Luna Ramírez



