# Buscador de Cocteles 🍹🔎

![Screenshots](https://github.com/Adalab/modulo-2-evaluacion-final-deligarbur/blob/main/public/images/Preview.png)

Este proyecto es una aplicación web desarrollada con HTML5, CSS3, SASS y JavaScript que te permite explorar y guardar tus cócteles favoritos de todo el mundo, utilizando la API abierta de [TheCocktailDB](https://www.thecocktaildb.com/).

## Estructura básica de carpetas

La estructura de carpetas sigue el esquema siguiente:

```
src
 ├─ scss (layout)
 |  ├─ footer
 |  ├─ header
 |  ├─ form (apartado de búsqueda)
 |  └─ results (listado de búsqueda y favoritos)
 |
 |
 └─ html (partials)
    ├─ footer
    ├─ header
    ├─ form (apartado de búsqueda)
    └─ results (listado de búsqueda y favoritos)

```

### 1. Funcionalidad básica

- Campo de texto y botón de búsqueda de cócteles.
- Botón de reset para limpiar búsqueda y resultados.
- Listado de resultados de búsqueda y de cócteles favoritos.

### 2. Búsqueda

- Conexión al API abierto de TheCocktailDB.
- Pre-carga de resultados de búsqueda por defecto.
- Pintado de tarjetas con imagen y nombre del cóctel.
- Validación para mostrar imagen de relleno en caso de falta de imagen.

### 3. Favoritos

- Funcionalidad para marcar cócteles favoritos.
- Listado de cócteles favoritos en pantalla.
- Persistencia de cócteles favoritos al recargar la página.

### 4. Almacenamiento local

- Listado de favoritos almacenado en localStorage.

### 5. Borrar favoritos

- Funcionalidad para borrar cócteles favoritos individualmente.
- Añadir/quitar como favorito al hacer clic en un cóctel.
- Resaltado de cócteles favoritos en resultados de búsqueda.
- Botón para borrar todos los favoritos a la vez.

## Instrucciones y uso

Para utilizar la aplicación, sigue estos pasos:

1. Clona o descarga el repositorio.
2. Abre una terminal y navega hasta la carpeta del proyecto.
3. Ejecuta npm install para instalar las dependencias.
4. Una vez instaladas las dependencias, ejecuta npm run dev.
5. Abre tu navegador web y dirígete a http://localhost:tu-host-local.
6. Utiliza el campo de búsqueda para buscar cócteles.
7. Marca tus cócteles favoritos y guárdalos en la lista de favoritos.
8. Disfruta explorando y gestionando tus cócteles favoritos! 🌟


¡Espero que disfrutes de esta experiencia con cócteles de todo el mundo! 🍹🌎


