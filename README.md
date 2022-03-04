# Starting2
Incluyendo algunas mejoras a Starting!
## Introducción
Luego de hacer mi primer miniproyecto quise seguir agregando mas funcionalidades a la aplicación.
Es por eso que presento una nueva versión de este proyecto!

## Objetivo de este repositorio
El objetivo de este proyecto fue programar con python una pequeña aplicación que me permita, mediante con interface (tkinter), ingresar una imagen de Gato o Perro y me de la predicción de lo observado.

Para ello utilicé una red convolucional.

En esta nueva versión agregué un nuevo botón para poder hacer la predicción sólo cuando el usuario lo solicita (con lo que con un poco más de investigación pude resolver mi desafío pendiente en la versión anterior!). Además agregué un ícono y título a la ventana.
## Materiales
En este HitHub subí dos archivos:
* RedConvolucionalGatosPerros.py: que es el código que use para entrenar la red. Este código se puede pegar en una Jupyter o en una Colab y correrlo.
Una vez entrenada (que toma un tiempo) usé el comando: 

> modelo.save('perros-gatos.h5')

Que permite exportar el modelo ya entrenado, para hacer las predicciones sin necesidad de volver a entrenar.
Esto genera un archivo con extensión .h5 que se debe guardar en la misma carpeta donde se va a desarrollar el proyecto de la aplicación.
* PrimerProyectoV0.pyw: es el código que usé para armar la interface y hacer la predicción.
Yo la corrí en Sublime Text.
La extención .pyw es para que cuando se abra la aplicación desde ese archivo no se abra la consola por detras.
## Desafíos pendientes
Seguir invertigando tkinter para mas proyectos!
