# Repaso completo de JS

Practica para repasar todos los conceptos básicos de JS

- Utilizando la estructuda de 'Base de datos' dada, la idea es resolver el siguiente problema:

Tenemos una empresa de Administración de casas, la cual tiene empleados que se dedican a consultar información de sus clientes.

La base de datos consta de 4 tablas:

- Usuarios
- Roles
- Clientes
- Casas

Los usuarios tienen acceso a una consulta por cliente para saber si tienen casa(y sus detalles).
Los usuarios tienen roles asignados de: Admin y Operario
A continuación se detalla los permisos:

- Operario: Puede ver los clientes, si existen o no, PERO NO PUEDE VER SUS PROPIEDADES.
- Admin: Tiene acceso total a todos los clientes y sus propiedades.

En el archivo index.js se encuentran todas las funciones que usted debe de desarrollar como mínimo, si lo requiere puede hacer más

La consulta a llamar se llama getInformación, y recibe como parametro:

- 1: ID del usuario que realiza la consulta
- 2: ID del cliente que quieren consultar

Las respuestas esperadas son las siguientes:

- Usuario no encontrado, intente con un usuario valido
- Cliente con el id: \$ID no fue encontrado en la Base de datos
