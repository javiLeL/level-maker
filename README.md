# Lever Maker 
Este software es un creador de videojuegos tanto para personas poco experimentadas en el mundo de la programacion como para personas que quieran crear un videojuego con el motor

## Uso de la aplicaccion

Aqui dividiremos a lo susarios que quieren hostear su propio servidor y los que quieren disfrutar de Lever Maker como un software normal

### Los usuarios Normales
#### Acceder a una base de datos
Instalaran el software y se dirigiran arriba a la derecha. El circulo rojo de la imagen.

![](https://github.com/javiLeL/level-maker/blob/main/doc/imgs/screenshots/Captura1.PNG?raw=true)

Esto nos abrira un nuevo apartado el cual deberemos de rellenar con los datos de nuestra base de datos este se ve tal que asi:

![](https://github.com/javiLeL/level-maker/blob/main/doc/imgs/screenshots/Captura2.PNG?raw=true)

Tras rellenar estos campos con los de la base de datos presionaremos el boton guardar
*(Esto tambien lo podemos hacer si queremos cambiar de base de datos)*.

#### Registrarse
Tras introducir los datos de la base de datos deberemos registrarnos si es que no lo estamos. Para ello nos seleccionaremos la opccion de registrarnos.
 

### Los usuario avanzados 
Estos deberan de usar un soporte de base de datos, ya sea `mySql` o compatibles con este como `mariaDB` y ejecutar los archivos sql que se encuentran en la carpeta [sql](https://github.com/javiLeL/lever-maker/tree/main/src/db/sql) esto creara las tablas necesarias para el correcto funcionamiento de la base de datos.

Para que los demas usuario se puedan conectar es necesario abir un puerto o solo funcionara en local.