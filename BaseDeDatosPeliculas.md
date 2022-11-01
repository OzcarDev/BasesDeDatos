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

## Modelo Relacional de BASE DE DATOS

![Imagen](https://media.discordapp.net/attachments/845392998648119356/1035210650500210688/Diagrama.jpg)

## Reglas de Negocio

- ### Película

1. Crear una película
1. Leer todas las películas
1. Leer una película en particular
1. Leer todas las películas de un género
1. Acutalizar una pelicula
1. Eliminar una película

- ### Director

1. Crear un director
1. Leer todos los directores
1. Leer un director en particular
1. Actualizar un director
1. Eliminar un director

- ### Género

1. Crear un género
1. Leer todos los géneros
1. Leer un género en particular
1. Actualizar un género
1. Eliminar un género

- ### Película/Director
1. Crear una autoría
1. Leeer todas las autorias
1. Leer una autoría en particular
1. Leer todas las autorías de una película
1. Leer todas las autorías de un director
1. Actualizar autoría
1. Elminar autoría.
