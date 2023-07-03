# Laboratorio-final-TD-UIDE

# Importar Librerías.
![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/301f491a-bfab-4db7-9c45-f2dd7b6fcfad)

# Carga de imágenes, lectura del dataset y creamos las etiquetas.
### Con los comando (tf.keras.utils.image_dataset_from_directory) cargamos los datos de cada imagen que exiten en cada clase, haciendo solo referencia a la carpeta TRAIN, que es la que vamos a evaluar.

![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/8bfb0f8b-b854-43c0-910c-dddf679c320e)

# Preprocesamos las imágenes.
### Realizamos el procesamiento de las imágenes de cada clase, mostramos un ejemplar de imagen por carpeta y en lo posterior crear el modelo que se va a utilizar para mejorar su calidad.

 ![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/3160edc9-084a-4e33-b21a-a3efcdda883d)

# Creamos el modelo.
### El modelo que aplicamos a esta practica es el Convolutional Neural Network (CNN) utilizando bibliotecas Keras.

### Las CNN se destacan en el procesamiento de imágenes debido a su capacidad para capturar y extraer características relevantes de las imágenes de manera automática. A diferencia de las redes neuronales tradicionales, las CNN utilizan capas convolucionales que aplican filtros de convolución a la entrada. Estos filtros detectan patrones locales, como bordes, texturas y formas en las imágenes.

![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/397dd211-42de-4eb0-aa3f-df9f4d261ce6)

### Con el siguiente comando, se puede mostrar el modelo y sus capas para ver los parámetros que se pueden evaluar, utilizamos ADAM (Adaptive Moment Estimation ) es un algoritmo de optimización que conbina los beneficios RMSprop y momentum.

![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/cecd35d1-6213-4f08-a8d3-c4d82cfad2a8)

# Entrenamos el modelo: Aprende a clasificar imágenes.
### En este paso puede tomar varios minutos, dependiendo de tu ordenador, cpu y memoria ram libre.

![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/9a688d11-3527-4999-b5e1-a6ea167e6bc3)

### Esta data guardamos, para reutilizarla en el futuro, sin tener que volver a entrenar.

![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/92cfcfd5-6f5f-4b65-9746-5f016fae0d3f)

# Evaluamos la red
### El modelo de CNN ha sido entrenado y evaluado utilizando un conjunto de datos de imágenes con 810 archivos pertenecientes a 8 clases diferentes. Durante el entrenamiento, el modelo alcanzó una precisión del 100%, mientras que durante la evaluación obtuvo una precisión del 85.8%.

![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/76618852-73fc-4cfe-b41d-7522911eedb3)

# Matrix confusión

![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/3af060bd-5889-4b99-b0cc-b9fbc054e6b8)
![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/103d3b2b-036a-47c1-96e7-8bd978139fcb)
 
# Procesamos una nueva imagen y verificamos su clasificación

 ![image](https://github.com/78wlado/Laboratorio-final-TD-UIDE/assets/136178520/36a3fc58-4b28-4644-841e-403b2aaeed69)

 
