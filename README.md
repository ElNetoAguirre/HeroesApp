<p align="center">
  <a href="https://www.angular.io/" target="blank"><img src="https://angular.io/assets/images/logos/angular/angular.svg" width="200" alt="Angular Logo"/></a>
</p>

# Héroes App

Aplicación creada utilizando **Angular Material** y **PrimeFlex**, y muestra un listado de Super Héroes, puedes seleccionar alguno de ellos y obtener más información sobre dicho Héroe, a demás, se puede agregar, editar o eliminar Héroes del listado.

Cuenta con un buscador, el cual muestra sugerencias o autocompleta al momento de empezar a escribir, si escribes algo que no exista, la aplicación te informará que la búsqueda no existe, validando la información con el Backend, que se conecta mediante **JSON-Server**, comunicándose con un CRUD.

Existe una sección con una pequeña área de *Autenticación* o *Login*, la cual no es funcional, pero sirve para mostrar el uso de diferentes estilos en los layouts de la aplicación.

Algunos conceptos utilizados para la generación de ésta App, son:

1. Rutas Hijas.
2. Rutas Principales.
3. LazyLoading.
4. Multiples estilos en la misma SPA.
5. Angular Material.
6. Interfaces y tipado.
7. Pipes personalizados.
8. Variables de entorno.
9. Autocomplete de Angular Material.
10. Peticiones HTTP.
11. JSON-Server.
12. PrimeFlex.
13. CRUD.
     - Create.
     - Read.
     - Update.
     - Delete.
14. Pipes puros e impuros.
15. Snacks.
16. Dialogs.
18. Protección de rutas.
19. Rutas privadas.
20. Rutas públicas.
21. Servicio de autenticación.
22. Angular Guards.
23. CanActivateFn.
24. CanMatchFn.
25. Mantener la sesión del usuario.

Este proyecto fue generado con [Angular CLI](https://github.com/angular/angular-cli) versión 16.1.1.

## Servidor de Desarrollo

1. Clona el proyecto para extraer los datos del repositorio.

2. Ejecuta `npm install` para descargar e instalar los paquetes necesarios para la ejecución de la app.

3. Levanta el Backend de la app con el comando `npm run backend` para acceder la base da datos local la cual correrá en la dirección `http://localhost:3000`.

4. Ejecuta `ng serve` para generar un servidor de desarrollo. Navega a `http://localhost:4200/`. La aplicación se recargará automáticamente si cambia alguno de los archivos de origen.
