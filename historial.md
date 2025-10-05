# HISTORIAL 

Tomando como base el TP3 que ya desarrollaron, agregar la siguiente funcionalidad:

## Base de datos

### Crear la tabla Historial que registre la cantidad de reproducciones que tiene una cancion con la siguiente estructura 
- historial_id - clave primaria (numerica - autoincremental)
- usuario_id : id de usuario que escucha la cancion (numerico)
- cancion_id : id de cancion escuchada (FK a canciones)
- fecha: fecha y hora de reproduccion

## Backend

### Crear los siguientes endpoints(rutas) para la url '/historial'
- POST: Crea un registro en la tabla , recibe usuario_id y cancion_id
- DELETE: Borra un registro de la tabla, recibe historial_id
- GET: devuelve todas las reproducciones de una cancion, recibe cancion_id

### Crear el controller historial.js que debe contener los 3 metodos a ser llamados desde los endpoints en index.js

## Entrega
1. La fecha de entrega es a partir del viernes 17 de octubre, puede ser cualquier martes o viernes por la mañana.
2. Se deben presentar ambos integrantes del grupo, con una notebook que tenga el codigo funcionando
3. Se va a evaluar que funcionen los endpoints, requeridos y que puedan explicar el codigo que hicieron. 
4. En particular el recorrido de un dato desde que sale de POSTMAN hasta que accede a la base de datos a traves de las 3 capas(front, back y SQL)

