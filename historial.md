Tomando como base el TP3 que ya desarrollaron, agregar la siguiente funcionalidad:

HISTORIAL
Base de datos:
Crear una tabla que registre la cantidad de reproducciones que tiene una cancion con la siguiente estructura
id - clave primaria numerica
usuario_id : id de usuario que escucha la cancion 
cancion_id : id de cancion escuchada
fecha: fecha y hora de reproduccion

Backend:
Crear los siguientes endpoints para la url '/historial'
POST: 
Crea un registro en la tabla , recibe usuario_id y cancion_id

DELETE:
Borra un registro de la tabla, recibe id

GET:
