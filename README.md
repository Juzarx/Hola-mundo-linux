# Hola mundo con linux

## Descripción

Guía para crear un programa hola mundo en c desde la consola de la distribución de linux ubuntu en una maquina virtual.






## Instalación 🛠

Para la instalacion de la maquina virtual utilizaremos VM Virtual Box desde el enlace (https://www.virtualbox.org/wiki/Downloads) y descargar la versión para windows.

También utilizaremos 23.10 de ubuntu desde el siguiete enlace (https://ubuntu.com/download/desktop/thank-you?version=23.10.1&architecture=amd64).

Instalamos el ISO ubuntu a la máquina virtual y asignamos los recursos necesarios.

    
## Utilizar la terminal ⚙

Una vez instalado ubuntu e iniciado sesión abrimos la terminal utilizando ctrl+alt+t o abriendo la aplicación terminal desde el centro de aplicaciones.

Una vez dentro de la terminal utilizamos el comando "sudo su" para iniciar sesión como superusuario (root).
Después utilizamos el codico "sudo apt update" paa actualizar los repositorios.

Ahora utilziamos el comando "nano hola_mundo.c" para abrir el editor nano y crear el archivo hola_mundo.c
## Código 📝

Con el editor nano abiero incluimos las librerias utilizando "include <stdio.h>".

utilizamos el siguiente código para el hola mundo: 

    int main() { 
    
    printf("Hola mundo!\n");

    return 0;
 
    }

Usamos ctrl + O para guardar guardar el archivo y presionamos enter.
Ahora con salimos del editor nano utilizando ctrl + X.

Escribimos el siguiente código en la terminal gcc hola_mundo.c -o hola_mundo

Ahora podemos ejecutar el código desde la consola de ubuntu utilizando ./hola_mundo

Captura de pantalla:

![image](https://github.com/Juzarx/Hola-mundo-linux/assets/166193236/08761f2d-e194-486b-9b00-edacb4699bef)

