# dany librery
libreria 
# Booknest


Booknest es una aplicación web básica desarrollada con HTML, CSS y JavaScript que permite la gestión sencilla de libros en una biblioteca o librería.

## Funcionalidades

- Login simple  
  - Usuario administrador: `admin@booknest.com`  
  - Contraseña: `1234`  
  - Los demás usuarios ingresan como clientes.  

- Panel de administrador  
  - Registrar nuevos libros con título, autor y estado.  
  - Visualizar todos los libros registrados.  
  - Eliminar libros.  

- Panel de cliente  
  - Ver únicamente los libros en estado "Disponible".  
  - Solicitar préstamo de un libro.  
  - Comprar un libro.  

- Persistencia de datos  
  - Los libros se almacenan en el navegador usando `localStorage`.  
  - Esto permite que los datos se mantengan aunque se recargue la página.  

## Tecnologías utilizadas

- HTML5 para la estructura.  
- CSS3 para los estilos y diseño.  
- JavaScript (Vanilla) para la lógica y manejo de datos.  

## Estructura del proyecto


-En el código inicial, el CSS y JS están incluidos en `index.html`

## Uso

1. Clona o descarga el repositorio.  
2. Abre el archivo `index.html` en tu navegador.  
3. Ingresa con:  
   - Admin → `admin@booknest.com / 1234`  
   - Cliente → cualquier otro correo/contraseña.  

