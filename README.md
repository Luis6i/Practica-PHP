# Practica-PHP

OBJETIVOS:

Dominio del patrón MVC básico de PHP (https://laravel.com/ o http://symfony.es/)

ENUNCIADO

Desde un formulario, un usuario introduce su user, password, y se loguea en una base de datos Oracle. 

A continuación, se comprueban si los datos de user / passw son correctos en la base de datos seleccionada y si es así, se muestra una interfaz donde se salude al usuario (buenos días, buenas tardes, buenas noches, según la hora del sistema). y se muestre en todo momento hasta la finalización de la sesión el nombre de la BBDD sobre la que se trabaja y el usuario.

Después se mostrará una interfaz con todos los usuarios de la tabla USUARIOS de la SGDB en cuestión. Donde se podrá realizar la gestión de los mismos, salvo eliminar el usuario “admin”. pass: 1234
Se entiende por gestión: Operaciones CRUD
alta de nuevos usuarios
eliminar usuarios (salvo “admin”)
modificar (salvo “admin”)
visualizar listado de usuarios.
Si el login es incorrecto, se mostrará un mensaje indicandolo (user / pass incorrectos) y se volverá a mostrar la página de login.
Añadir boton logout y tantos botones necesites como para permitir navegación en la aplicación. (sin utilizar los botones del navegador).
