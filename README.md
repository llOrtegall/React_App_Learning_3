Crea una aplicación para buscar películas

Correr App en Desarrollo:
1. npm install ---> instalación de las dependencies utilizadas en este proyecto
2. npm run dev ---> inicializar aplicación en puerto local

API a usar:

--https://www.omdbapi.com/?apikey=4fd5a756&s={busuqeda}
--API_KEY: En El Correo.

Requerimientos:

- primera iteración:

✅ 1. Necesita mostrar un input para buscar la pelicula y un botón para buscar.
✅ 2. lista las peliculas encontradas y muestra el título, año y poster
✅ -- Que el formulario funcione
✅ 3. haz que las películas se muestren en un grid responsive
✅ -- Hacer el fetching de datos a la API


- Segunda iteración:

✅ 4. Evitar que se gala la misma búsqueda dos veces seguidas.
5. Haz que la búsqueda se haga automaticamente al escribir
6. Evita que se haga la búsqueda continuamente al escribir(debouce)