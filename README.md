# Lever Maker 
Este software es un creador de videojuegos tanto para personas poco experimentadas en el mundo de la programacion como para personas que quieran crear un videojuego con el motor

# Uso de la aplicaccion

Aqui dividiremos a lo susarios que quieren hostear su propio servidor y los que quieren disfrutar de Lever Maker como un software normal

## Los usuarios Normales
### Acceder a una base de datos
Instalaran el software y se dirigiran arriba a la derecha. El circulo rojo de la imagen.

![](https://github.com/javiLeL/level-maker/blob/main/doc/imgs/screenshots/Captura1.PNG?raw=true)

Esto nos abrira un nuevo apartado el cual deberemos de rellenar con los datos de la base de datos que se va a utilizar para alvergar la información

Tras rellenar estos campos con los de la base de datos presionaremos el boton guardar
*(Esto tambien lo podemos hacer si queremos cambiar de base de datos)*.

### Registrarse
Tras introducir los datos de la base de datos deberemos registrarnos si es que no lo estamos. Para ello nos seleccionaremos la opccion de registrarnos.

![](https://github.com/javiLeL/level-maker/blob/main/doc/imgs/screenshots/Captura3.PNG?raw=true)

Tras esto nos aparecera un formulario el cual deberemos rellenar, tras esto seleccionaremos el boton de registratse y si todo va bien nos habremos registrado.

Una vez registrados cuando queramos volver ha acceder a nuestro contenido solo debemos iniciar sesión. 

### Iniciar sesión

Para ello deberemo simplemente reiniciar el programa si ya estamos con una sesion iniciada o salir del apartado donde nos econtremos y dirigirnos al apartado de inicio de sesión y rellenaremos los datos que nos piden

### Creacion y Edicion de Niveles

Tras acceder a nuestro contenido si esta vacio solo podremos crear nuevos niveles al hacer esto nos permitira poner nombre al nivel, escribiremos el nombre de nuestra elección crearemos el nivel para posteriormente editarlo.
Despues de hacer esto entraremos en el modo ediccion en el cual podemos elegir bloques y ponerlos en el mapa.

#### **Controles**
Para poder moverse por el modo edito es necesario tener los controles en mente estos son

| Tecla                         | Accion                          |
| ----------------------------- | ------------------------------- |
| `r`                           | Rota 90º el bloque selecciónado |
| `click izquierdo`             | Colocal un bloque seleccionado  |
| `click derecho`               | Borrar un bloque ya colocado    |
| `click central` + `arrastrar` | Permite mover la camara         |
| `esc`                         | Salir del **modo creacción**    |

Para salir del modo editor seleccionaremos el boton de arriba a la izquierda y seleccionaremos la opccion guardar y salir. Tal y como se muestra en la presentación:

![](https://github.com/javiLeL/level-maker/blob/main/doc/videos/modo-editor.gif?raw=true)

### Jugar Niveles

Tras crear un nivel podremos jugarlo para ello lo seleccionaremos y presionaremos jugar nivel esto nos abrira el **Modo Juego** el cual cargara todas las colisiones del nivel creado.

#### **Controles**

| Tecla     | Accion                   |
| --------- | ------------------------ |
| `a`       | Moverse a la izquierda   |
| `d`       | Moverse a la derecha     |
| `espacio` | Saltar                   |
| `esc`     | Salir del **modo juego** |

Pequeño ejemplo de como se ve el modo juego:

![](https://github.com/javiLeL/level-maker/blob/main/doc/videos/modo-juego.gif?raw=true)

### Borrar niveles 

Si deseamos borrar un nivel lo seleccionaremos y presionaremos el boton borrar este no se borrar de inmediato ya que por motivos de seguridad devemos de presionar el boton aceptar 2 veces.

## Los usuario avanzados 

Se entendera a usuarios avanzados como personas que poseen ciertos conocimientos con la programación o minimo uso de bases de datos si no es tu caso y aun asi quieres hacerlo puede apoyarte de vario tutoriales para lograrlo.

Estos deberan de usar un soporte de base de datos, ya sea `mySql` o compatibles con este como `mariaDB` y ejecutar los archivos sql que se encuentran en la carpeta [sql](https://github.com/javiLeL/lever-maker/tree/main/src/db/sql) esto creara las tablas necesarias para el correcto funcionamiento de la base de datos.

Para que los demas usuario se puedan conectar es necesario abir un puerto o solo funcionara en local.