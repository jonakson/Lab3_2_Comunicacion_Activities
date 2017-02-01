# Lab3 - Comunicación bidireccional entre Activities #

## Descripción del problema ##
Crea un proyecto con dos actividades similares a la UI propuesta. Cuando se pulse el botón “Verificar” se lanza la segunda actividad a la que se le pasará como parámetro el nombre introducido en el EditText y mostrará en el TextView:
> “Hola ” + nombre recibido + ” ¿Aceptas las condiciones?”.

En esta actividad se podrán pulsar dos botones, de forma que se devuelva a la actividad principal el String “Aceptado” o “Rechazado”, según el botón pulsado. Al pulsar cualquier botón se regresará a la actividad anterior. En la actividad principal se modificará el texto del último TextView para que ponga “Resultado: Aceptado” o “Resultado: Rechazado”, según lo recibido.

## Capturas de la aplicación ##

Vista inicial de la aplicación. Aquí tenemos el EditText en el que introduciremos el nombre del usuario y el botón que nos llevará a la nueva Activity.

<img src="https://dl.dropboxusercontent.com/u/52992573/PGL/Lab3/Lab3_2_Comunicacion_Activities_001.png" width="300">

Aspecto de la Activity lanzada. Podemos elegir si aceptar o rechazar las condiciones.

<img src="https://dl.dropboxusercontent.com/u/52992573/PGL/Lab3/Lab3_2_Comunicacion_Activities_002.png" width="300">

Si aceptamos las condiciones nos aparecerá este TextView en la Activity inicial.

<img src="https://dl.dropboxusercontent.com/u/52992573/PGL/Lab3/Lab3_2_Comunicacion_Activities_003.png" width="300">

Si rechazamos las condiciones nos aparecerá este TextView en la Activity inicial.

<img src="https://dl.dropboxusercontent.com/u/52992573/PGL/Lab3/Lab3_2_Comunicacion_Activities_004.png" width="300">
