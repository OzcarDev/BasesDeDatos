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
    - director_id
    - Nombre **__PK__**
    - Biografía 

- Género
    - Nombre **__PK__**
    - Descripción
    
- Pelicula/Director
     - ID **__PK__**
     - Película **__FK__**
     - Director **__FK__**