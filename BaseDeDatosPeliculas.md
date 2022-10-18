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