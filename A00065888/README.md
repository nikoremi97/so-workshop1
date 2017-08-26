## Taller 1  

**Nombre:** Nicolas Recalde  

**Código:** A00065888

## Soluciones 


### 1.  
La raíz de un directorio en Linux es el nivel con la vista mas alta del directorio, es decir, el contenedor de todo el directorio. Todos los demás directorios y ficheros están debajo de la raíz.

| Directorio   | Archivo ejemplo | Descripción del contenido del directorio  |
|------|------|------|
| /bin | echo  | aplicaciones binarias importantes   |
| /boot  | grub  |  Ficheros de configuración del arranque   |
| /dev | ht0  | los ficheros de dispositivo   |
| /etc | passwd  | ficheros de configuración, scripts de arranque, etc   |
| /home | tecmint   | directorios personales (home) para los diferentes usuarios   |
| /initrd | mkinitrd   | usado cuando se crea un proceso de arranque initrd personalizado.   |
| /lib |  libreadline.so.3 | librerías del sistema   |
| /lost+found  |  -rw-r--r-- 1 root root 110891 Oct 5 14:14 #388200  | - proporciona un sistema de "perdido+encontrado" (lost+found) para los ficheros que existen debajo del directorio raíz   |
| /media | v4l2grab.c  |  particiones montadas automáticamente en el disco duro y medios   |
| /mnt | cdrom  | sistemas de archivos montados manualmente en el disco duro   |
| /opt | someapp  |  proporciona una ubicación donde instalar aplicaciones opcionales    |
| /proc | meminfo  | directorio dinámico especial que mantiene información sobre el estado del sistema, incluyendo los procesos actualmente en ejecución   |
| /root | anaconda-ks.cfg  | directorio personal del usuario root   |
| /sbin | fastboot |  binarios importantes del sistema   |
| /srv | /srv/physics/www  | puede contener archivos que se sirven a otros sistemas     |
| /sys | bloc  |archivos del sistema (system)    |
| /tmp | someawesomeexample  | temporary files   |
| /usr | /usr/X11R6/lib  | plicaciones y archivos a los que puede acceder la mayoría de los usuarios   |
| /var | /var/backups | archivos variables como archivos de registros y bases de datos   |

   
### 2.  
| Comando   | Usuario | Descripción   |
|------|------|------|
| $ cat | root|  permite visualizar el contenido de un archivo de texto sin la necesidad de un editor  |
| $ cp   | root   |  copia un archivo o directorio origen a un archivo o directorio destino  |
| $ mv   | root  |  mueve un archivo a una ruta específica, y a diferencia de cp, lo elimina del origen finalizada la operación  |
|  $ rm  | root  | es el comando necesario para borrar un archivo   |
|  $pwd  | root  |  imprime nuestra ruta o ubicación al momento de ejecutarlo  |
| $ iwconfig  | root  | Muestra información de las tarjetas de red inalámbrica (wireless) que haya instaladas en el equipo   |
| $ date  | root  | Muestra la hora y la fecha   |
| $ cksum    | root  | Muestra el CRC del fichero y el tamaño en bytes   |
| $ whereis  | root  | Busca los archivos ejecutables, las fuentes y el manual de un comando   |
| $ sysctl  | root  | Muestra o modifica valores del kernel en tiempo de ejecución   |

### 3.
Me resultó más fácil compartirte este link en drive para que veas la evidencia de mi trabajo
https://docs.google.com/document/d/13GsUwOQgaWRDZO7PQ0zbf8VZf-nLPQEtUxv8rhAf26w/edit?usp=sharing

## Referencias

https://github.com/ICESI/so-commands/tree/master/centos7
https://help.ubuntu.com/kubuntu/desktopguide/es/directories-file-systems.html
https://hipertextual.com/archivo/2014/04/comandos-basicos-terminal/
http://www.ajpdsoft.com/modules.php?name=News&file=article&sid=155
http://www.sysadmit.com/2016/04/linux-variables-de-entorno-permanentes.html
https://docs.google.com/document/d/13GsUwOQgaWRDZO7PQ0zbf8VZf-nLPQEtUxv8rhAf26w/edit?usp=sharing
