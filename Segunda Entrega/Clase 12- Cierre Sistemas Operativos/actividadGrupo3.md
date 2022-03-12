## ¿Que es un usuario root en linux?

En sistemas operativos del tipo Unix, el superusuario o root es el nombre convencional de la cuenta de usuario que posee todos los derechos en todos los modos (monousuario o multiusuario). Normalmente es la cuenta de administrador.

---

## Investigar y establecer contraseña en ubuntu

Conviene de la que viene por defecto y usar sólo la del usuario que va a usar la computadora.

---

## Proceso para cambiar la contraseña de usuario en Ubuntu y derivados

Para poder realizar este proceso necesitamos usar la línea de comandos en Ubuntu, por lo que puedes abrir una buscando la terminal en tu menú de aplicaciones o con el atajo de teclas “Ctrl + Alt + T”.
Ahora debemos de iniciar sesión como usuario root, pues solo un usuario root puede cambiar su propia contraseña, para ello en la terminal vamos a teclear el siguiente comando:

**sudo -i**

El sistema les pedirá que ingresen la contraseña de sudo actual. Hecho esto, para cambiar la contraseña del usuario root, en la terminal vamos a teclear el siguiente comando:

**passwd**

Cuando ingresen el comando password, el sistema les pedirá que ingresen la nueva contraseña para su usuario root, después el sistema les pedirá que vuelvan a escribir la nueva contraseña. Después de hacerlo, el sistema confirmará que la contraseña se actualiza correctamente.
Ahora, siempre que necesite iniciar sesión como root o realizar cualquier operación de instalación y configuración que requiera una autorización de root, estará utilizando esta nueva contraseña.
Ya hecho este proceso basta con cerrar la sesión de root, para ello en la terminal debemos de teclear el siguiente comando:

**exit**

Pero qué sucede cuando se requiere cambiar la contraseña de otro usuario si eres el administrador del sistema.
Proceso típico
En Linux, el flujo de control durante el arranque es desde el BIOS, al gestor de arranque y al núcleo (kernel). El núcleo inicia el planificador (para permitir la multitarea) y ejecuta el primer espacio de usuario (es decir, fuera del espacio del núcleo) y el programa de inicialización (que establece el entorno de usuario y permite la interacción del usuario y el inicio de sesión), momento en el que el núcleo se inactiva hasta que sea llamado externamente.
La etapa del cargador de arranque no es totalmente necesaria. Determinadas BIOS pueden cargar y pasar el control a Linux sin hacer uso del cargador. Cada proceso de arranque será diferente dependiendo de la arquitectura del procesador y el BIOS.

---

## Para identificar los procesos en linux

Para visualizar los procesos que un usuario en particular está ejecutando utilizamos ps -u.

**ps -u (nombredeusuario)**
