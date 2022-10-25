# Base de datos sobre mis peliculas favoritas

## Entidades

- Película
    - pelicula_id **__PK__**
    - Título 
    - Guionista 
    - Fecha de estreno
    - Género **__FK__**
    - Calificación

- Director
    - director_id  **__PK__**
    - Nombre
    - Biografía 

- Género
    - genero_id  **__PK__**
    - Nombre 
    - Descripción

- Pelicula/Director
     - id_p/d **__PK__**
     - Película **__FK__**
     - Director **__FK__**


## Relaciones
    1. Una película pertenece a género (1-M)
    1. Una película tiene un director (1-1)
    1. Un director poseé película (1-M) 

## Tabla

![Imagen](https://media.discordapp.net/attachments/889289823855194132/1034479462248624189/MiDiagrama.jpg)