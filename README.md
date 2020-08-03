# Método para clasificación del dataset Cifar-10 usando método de normalización MEAN
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Cuando empezamos a realizar un proyecto de Machine Learning o de Inteligencia artificial, empezamos seleccionando el dataset mas adecuado para cumplir con nuestros objetivos de investigacion, sin embargo, antes de empezar debemos tomar en cuenta el como se trataran estos datos debido a que dependiendo de los datos nuestros modelos de Machine Learning trabajaran mejor o peor esto tambien afecta al tiempo de ejcucion pues como ser corto como largo, teniendo esto en cuenta nos hemos propuesto investigar que tanto afecta la normalizacion de los datos en el tiempo en la presici con del modelo, poniendo a prueba 3 tipos de normalizacion los mas conocidos estos son: max-min, media, desviacion y la mas comun que es dividir para 255, compararemos sus resultados en tiempo y en presicion y determinar cual es el mejor metodo
de normalizacion para nuestro dataset. 
Como objetivo principal es que, a mas de revisar si afecta en mayor o menor medida el accuracy, es revisar los tiemposhen los que se tarda las redes neuronales convolucionales con diferentes arquitecturas, con la normalizacion dada, para la cual usaremos todo el conjunto de datos que en nuestro caso usaremos el dataset Cifar-10.

### Los cuadernos proporcionan los siguientes flujos de trabajo:
- CNN_MEAN: Carga del dataset, aplicación normalizacion MEAN al conjunto de datos, creación de una CNN y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- CNN_MIN_MAX: Carga, aplicación normalizacion min_max al conjunto de datos, creación de una CNN y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- CNN_NORMALIZACION_ESTANDAR: Carga, aplicación normalizacion estandar al conjunto de datos , creación de una CNN y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- LeNet_5_MIN_MAX: Carga, aplicación normalizacion min_max al conjunto de datos, creación de una CNN con una arquitectura clasica LeNet5 y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- LeNet_5_MEAN:Carga del dataset, aplicación normalizacion MEAN al conjunto de datos, creación de una CNN con una arquitectura clasica LeNet5 y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- LeNet_5_NORMALIZACION_ESTANDAR: Carga del dataset, aplicación de normalizacion estandar al conjunto de datos, creación de una CNN con una arquitectura clasica LeNet5 y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).

### Requerimientos
 - Python 3.6
 - Dataset CIFAR-10 Dataset. https://www.cs.toronto.edu/~kriz/cifar.html. Ultima descarga 20/07/2020.
### Dependencias                                                                              
- matplotlib (v3.3.0)
- keras (v2.2.4)
- numpy (v1.19.1)    
- tensorflow (v2.3.0)
- time (v3.7)
- tarfile (v3.8.5)
### Referencias  
[1] Learning Multiple Layers of Features from Tiny Images, Alex Krizhevsky, 2009.

[2] A. (2018). amir-saniyan/AlexNet. GitHub. https://github.com/amir-saniyan/AlexNet

[3] Rizwan, M. R. (2018, 14 septiembre). LeNet-5 – A Classic CNN Architecture. engMRK. https://engmrk.com/lenet-5-a-classic-cnn-architecture/
