# HISTORIAL 

Tomando como base el TP3 que ya desarrollaron, agregar la siguiente funcionalidad:

## Base de datos

### Crear la tabla **Playlist** que permite guardar un conjunto de canciones con la siguiente estructura
- playlist_id: clave primaria (numerica)
- cancion_id : id de cancion escuchada (fk a canciones)

## Backend

### Crear los siguientes endpoints(rutas) para la url '/playlist'
- POST: Agrega una cancion a una playlist: recibe playlist_id y cancion_id
- DELETE: Borra una cancion de una playlist:  recibe playlist_id y cancion_id
- GET: devuelve todas las canciones de una playlist: recibe playlist_id
- 
### Crear el controller playlist.js que debe contener los 3 metodos a ser llamados desde los endpoints en index.js

## Entrega
- La fecha de entrega es a partir del viernes 17 de octubre, puede ser cualquier martes o viernes por la mañana.-
- Se deben presentar ambos integrantes del grupo, con una notebook que tenga el codigo funcionando
- Se va a evaluar que funcionen los endpoints, requeridos y que puedan explicar el codigo que hicieron. 
- En particular el recorrido de un dato desde que sale de POSTMAN hasta que accede a la base de datos a traves de las 3 capas(postman, backend y SQL)
