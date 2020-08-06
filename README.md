# Método para clasificación del dataset Cifar-10 usando método de normalización MEAN
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

El aprendizaje automático es sensible a la etapa de preparación de los datos, especialmente cuando se trabaja con conjuntos de datos de imágenes, dentro de los cuales se pueden aplicar muchos métodos, incluida la normalización. En este trabajo proponemos una arquitectura de red neural convolucional que incorpora un procesamiento utilizando las técnicas de normalización más conocidas por el estado del arte, en esta investigación demostraremos cuáles son las que nos dan mejores resultados y se integra mejor a nuestra arquitectura de red neural convolucional para el conjunto de datos de Cifar-10 y lo compararemos con varios modelos. Para esta investigación utilizamos la medida de calidad de la precisión para demostrar mejores resultados en la clasificación de imágenes, reduciendo al mismo tiempo el tiempo de ejecución. Esta investigación abre las puertas a futuras investigaciones sobre la incorporación de nuevas técnicas de procesamiento de las redes neuronales convolucionales (CNN) en nuevas estructuras para la mejora de los resultados de las CNN.   

### Los cuadernos proporcionan los siguientes flujos de trabajo:
- AlexNet(CNN): Carga del dataset, aplicación normalizacion MEAN al conjunto de datos, creación de una CNN (AlexNet) y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- AlexNet_MIN_MAX: Carga, aplicación normalizacion min_max al conjunto de datos, creación de una CNN (AlexNet) y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- AlexNet_NORMALIZACION_ESTANDAR: Carga, aplicación normalizacion estandar al conjunto de datos , creación de una CNN (AlexNet) y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- MYDNET_MEAN: Carga del dataset, aplicación normalizacion MEAN al conjunto de datos, creación de una CNN y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- MYDNET_MIN_MAX: Carga, aplicación normalizacion min_max al conjunto de datos, creación de una CNN y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
- MYDNET_NORMALIZACION_ESTANDAR: Carga, aplicación normalizacion estandar al conjunto de datos , creación de una CNN y entrenamiento del modelo, ademas de la muestra de los resultados obtenidos (acc, tiempo).
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
