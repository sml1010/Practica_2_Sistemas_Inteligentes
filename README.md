# Práctica 2 Sistemas Inteligentes
Repositorio creado y desarrollado por una alumna del grupo 102 de la asignatura "Sistemas Inteligentes Aplicados a la Salud" del grado en Ingeniería de la Salud en la Universidad de Burgos. 

## Autor/a
Sara Meda López
 
## Título del proyecto
*Reconocimiento de formas con redes neuronales*

![EMNIST](https://github.com/user-attachments/assets/496396d0-eda5-4f5c-93d5-e994b5a49bd8)

## Supuesto práctico
Se dispone de varias carpetas en las que se encuentran imágenes de CT de diferentes sujetos y diferentes tipos de adquisiciones (cerebral, torax, cuerpo completo) en formato Dicom. El departamento de radiología del hospital en el que estás trabajando solicita la realización de un procesamiento de dichas imágenes de forma que se obtenga la imagen segmentada en el mayor número de regiones posible para cada uno de los sujetos.

## Introducción
### Imágenes MNIST
En esta práctica se va a trabajar con el reconocimiento de formas (pattern recognition, en inglés).
Las imágenes con las que se va a trabajar pertenecen a la familia de imágenes MNIST, cuya versión original se puede obtener en http://yann.lecun.com/exdb/mnist/(URL verificada en octubre del 2024).
MNIST significa Modified NIST, donde, a su vez, NIST quiere decir National Institute of Standards and Technology. La palabra clave es modified. MNIST se constituye de una serie de imágenes de dígitos escritos a mano alzada, entre 0 y 9. Cada dígito está representado por una imagen en blanco y negro.

### Objetivos
En esta práctica se emplearán las imágenes de num-MNIST y se cubrirán los siguientes puntos:

- Obtener un conjunto de datos, donde:
 será un conjunto de atributos que describa una imagen. En este caso tomaremos los valores de los píxeles de una imagen.
 será la clase

- Dividir el conjunto de datos (imágenes, en nuestro caso) en dos partes:
(1) un conjunto de entrenamiento
(2) un conjunto de test.

- Entrenar una red neuronal con la parte de los datos que forma el conjunto de entrenamiento y comprobar su funcionamiento con otra parte (conjunto de test), para la obtención de la tasa de acierto en el perceptrón simple.
Empleando el perceptrón propio.
Empleando la red neuronal de Sklearn

- Manejar diferentes métricas y herramientas para testear un clasificador.
Matriz de confusión
Métricas:
Exactitud
Precisión
Sensibilidad

- Implementar una red neuronal multicapa que permita clasificar todos los grupos de imágenes.

- Introducir la validación cruzada como estrategia de valoración de un clasificador.

- Añadir un nuevo conjunto de datos de test y obtener los resultados de rendimiento de las diferentes redes neuronales implementadas.

## Tareas a realizar
Implementar todas las tareas incluidas en el noteBook "Practica2-Enunciado":
- **Tarea 1**: Implementación de la función crea_diccionario
- **Tarea 2**: Implementación de la función getdataset
- **Tarea 3**: Obtener la matriz de confusión para la predicción de 'A's en el conjunto de 'A' y '3' empleando las funciones entrena_perceptron, predice y evalua.
- **Tarea 4**: Valoración de resultados repitiendo la creación de grupos de entrenamiento y predicción.
- **Tarea 5**: Analizar la matriz de confusión y sus correspondientes métricas para todos los diferentes pares de imágenes de MNIST.
- **Tarea 6**: Perceptrón múltiple y nuevos datos de test.
- **Tarea 7**: Análisis y conclusiones de los resultados obtenidos para la clasificación de imágenes, tanto con el perceptrón simple como multicapa y comparación con nuevos datos de test.
  
Crea los notebooks que necesites para mostrar los resultados solicitados. Todas las funciones implementadas deben encontrarse en un archivo .py y se deben exportar de forma correcta en cada notebook.

## Documentos a entregar
- Repositorio privado en GitHub que incluya la carpeta con los archivos necesarios para ejecutar los pasos propuestos en la práctica así como los notebooks desarrollados para la realización de las diferentes pruebas y análisis. Debes añadir como colaborador al repositorios al usuario davgarciagarcia.
- En el buzón de entrega del aula virtual, documento pdf que incluya el detalle de las comparaciones y resultados de los análisis implementados.
