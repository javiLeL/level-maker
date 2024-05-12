# Lever Maker 
Este software es un creador de videojuegos tanto para personas poco experimentadas en el mundo de la programacion como para personas que quieran crear un videojuego con el motor

## Uso de la aplicaccion

Aqui dividiremos a lo susarios que quieren hostear su propio servidor y los que quieren disfrutar de Lever Maker como un software normal

### Los usuarios Normales
Instalaran el software y en los archivos de configuracion de la base de datos pondran la `ip`, `puerto`, `nombre de la base de datos`, `nombre del usuario de la base de datos` y `contrasena de la base de datos`.

### Los usuario avanzados 
Estos deberan de usar un soporte de base de datos, ya sea `mySql` o compatibles con este como `mariaDB` y ejecutar los archivos sql que se encuentran en la carpeta [sql](https://github.com/javiLeL/lever-maker/tree/main/src/db/sql) esto creara las tablas necesarias para el correcto funcionamiento de la base de datos.

Para que los demas usuario se puedan conectar es necesario abir un puerto o solo funcionara en local.