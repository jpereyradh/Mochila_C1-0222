

# Hola mundo

## Hola mundo

## Que es un usuario root en Linux?

El usuario root, el usuario cuyo nombre de inicio es "root", tiene características especiales:

Root es una cuenta de usuario que tiene un control absoluto de todo lo que ocurre en un sistema. Es decir, que si rooteamos nuestro sistema podremos acceder a todas sus funciones con todo lo que ello conlleva. 

 ¿Por qué ubuntu no me deja establecer la contraseña durante la
instalación? 

Por defecto, viene definida la clave root como root. Los scripts que realizan las instalaciones,  utilizan esta clava para poder acceder al sistema.


¿Cuáles son los procesos típicos de Linux?

systemd es un conjunto de demonios o daemons de administración de sistema, bibliotecas y herramientas diseñados como una plataforma de administración y configuración central para interactuar con el núcleo del Sistema operativo GNU/Linux

linux programs tipicos. ¿Cómo identificarlos?.

Comando top nos muestra un listado de los procesos en ejecucion, con sus respectivos tiempos de ejecucion.
Tambien muesta el uso de memoria y de CPU.
Comando ps nos permite ver los procesos que estan corriendo en nuestro sistema.
Comando free nos muestra la informacion de la memoria y el uso de la CPU.
Comando df nos muestra la informacion de los discos.


Investigar y establecer una contraseña para el usuarioroot.


Ahora debemos de iniciar sesión como usuario root, pues solo un usuario root puede cambiar su propia contraseña, para ello en la terminal vamos a teclear el siguiente comando:
1 sudo -i

El sistema les pedirá que ingresen la contraseña de sudo actual. Hecho esto, para cambiar la contraseña del usuario root, en la terminal vamos a teclear el siguiente comando:
1 passwd





