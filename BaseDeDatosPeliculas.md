# Base de datos sobre mis peliculas favoritas

## Entidades

- Película
     - Título **__PK__**
    - Guionista 
    - Director **__FK__**
    - Fecha de estreno
    - Género **__FK__**
    - Sinopsis
    - Mi calificación

- Director
    - Nombre **__PK__**
    - Pequeña biografía
    - Pelicula/Director **__FK__**
    - Mi película favorita de el
    - Año de debut
    
- Género
    - Nombre **__PK__**
    - Descripción
    - Género/Pelicula **__FK__**

- Género/Pelicula
    - ID **__PK__**
    - Película **__FK__**
    - Género **__FK__**


- Pelicula/Director
     - ID **__PK__**
     - Película **__FK__**
     - Director **__FK__**