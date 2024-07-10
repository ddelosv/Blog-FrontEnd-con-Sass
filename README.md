# Desafío - Blog FrontEnd con Sass

Este proyecto web ha sido desarrollado siguiendo el patrón 7-1 y cumple con los siguientes requisitos:

## Requisitos Completados

### 1. Crear los parciales requeridos en su respectivo directorio

Se han creado los parciales necesarios dentro de sus respectivos directorios para mantener una estructura ordenada y modular del código.

### 2. Importar los parciales correctamente dentro del manifiesto siguiendo el orden de carga del patrón 7-1

Todos los parciales han sido importados correctamente en el archivo de manifiesto, siguiendo el orden de carga recomendado por el patrón 7-1.

### 3. Crear página de registro

- [**Página de Registro:**](https://ddelosv.github.io/Blog-FrontEnd-con-Sass/registro.html "Title") Se ha creado una página de registro que simula el registro de datos del usuario.
- [**Redirección al Login:**](https://ddelosv.github.io/Blog-FrontEnd-con-Sass/login.html "Title") Al presionar el botón "Registrar", el usuario es redirigido a la página de Login.
- **Redirección al Inicio:** En la página de Login, al presionar el botón "Iniciar sesión", el usuario es redirigido a la página principal.

### 4. Crear la página de detalle del post

Se ha creado una página de detalle [**Boostrap**](https://ddelosv.github.io/Blog-FrontEnd-con-Sass/bootstrap.html "Title"), y se ha agregado el enlace a esta página **(desde la imagen de bootstrap en la sección novedades en index.html).**
 

### 5. Crear el componente de subscripción

Se ha añadido un componente de subscripción al final de la página principal, justo encima del footer.

### 6. Uso de mixins y variables

Se ha utilizado variables, mixis y nesting, que Permite escribir estilos de manera más eficiente y organizada.

## Estructura del Proyecto:

```plaintext
Desafío - Blog FrontEnd con Sass
├──assets
│    ├───css
│    ├───img
│    │   ├───logos
│    │   └───posts
│    └───sass
│        ├───abstracts
│        ├───base
│        ├───components
│        ├───layout
│        ├───pages
│        ├───themes
│        └───vendors
│
├── index.html
├── login.html
├── registro.html
└── bootstrap.html
