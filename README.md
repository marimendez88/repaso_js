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
- Su usuario cuenta con permisos de operario :Cliente con el id: \$ID no fue encontrado en la Base de datos
- Su usuario cuenta con permisos de operario : El cliente a consultar es: \$TODOS LOS DATOS
- Su usuario cuenta con permisos de admin: El cliente $nombre $apellido, tiene 1 casa ubicada en $ubicacion, con $cuartos cuartos, y se llama: \$nombreCasa
- Su usuario cuenta con permisos de admin: El cliente $nombre $apellido, no tiene casas asociadas a su perfil
- Su usuario cuenta con permisos de admin: El cliente con el id \$id no pudo ser encontrado en la base de datos.

## Reglas

Debe de utilizar:

- Templates String en todas las respuestas
- Todas las funciones deben de ser Arrow
- Debe utilizar Destructuring al menos una vez (recomendado, al guardar los datos para dar las respuestas)
- Puede utilizar callbacks, promises y async functions en cualquier caso que lo requiera.
- Usar obligatoriamente al menos 1 Async y Await
