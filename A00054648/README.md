# Taller 1

**Nombre:** Luis Alejandro Tróchez  

**Código:** A00054648

## Descripción  
Corta descripción de loa prendido 

### 1  

/bin - aplicaciones binarias importantes

/boot - Ficheros de configuración del arranque, núcleos y otros ficheros necesarios para el arranque (boot) del equipo.

/dev - los ficheros de dispositivo

/etc - ficheros de configuración, scripts de arranque, etc.

/home - directorios personales (home) para los diferentes usuarios.

/initrd - usado cuando se crea un proceso de arranque initrd personalizado.

/lib - librerías del sistema (libraries)

/lost+found - proporciona un sistema de "perdido+encontrado" (lost+found) para los ficheros que existen debajo del directorio raíz (/)

/media - particiones montadas (cargadas) automáticamente en el disco duro y medios (media) extraíbles como CDs, cámaras digitales, etc.

/mnt - sistemas de archivos montados manualmente en el disco duro.

/opt - proporciona una ubicación donde instalar aplicaciones opcionales (de terceros)

/proc - directorio dinámico especial que mantiene información sobre el estado del sistema, incluyendo los procesos actualmente en ejecución

/root - directorio personal del usuario root (superusuario); también llamado "barra-root".

/sbin - binarios importantes del sistema

/srv - puede contener archivos que se sirven a otros sistemas

/sys - archivos del sistema (system)

/tmp - temporary files

/usr - aplicaciones y archivos a los que puede acceder la mayoría de los usuarios

/var - archivos variables como archivos de registros y bases de datos



--Algunos archivos en las diferentes carpetas--

/bin/cat Utility to concatenate files to standard output
/boot/chain.b Used to boot non-Linux operating systems
/dev/lp0 (First printer port, LPT1) First parallel port (printers, scanners, etc)
/etc/X11: Ficheros para la configuración del sistema X Window
/lib/kbd Contains various keymaps
/dev/sda que representa nuestro disco duro sata
/sbin/shutdown Script to shutdown the OS
/srv/www Servidor web apache 
/usr/bin: Subdirectorio que almacena los archivos ejecutables del software que tenemos almacenado en nuestro ordenador
/var/lib: En este subdirectorio encontramos información sobre el estado de las aplicaciones. Este directorio también contiene bases de datos del sistema
### 2

Reading a log file in real time: In situations where you need to analyze the logs while the application is running, you can use the tail command with -f option.
tail -f path_to_Lo


-Use less to read files: To see the contents of a file, cat is not the best option especially if it is a big file. cat command will display the entire file on your screen. You can use Vi, Vim or other terminal based text editors but if you just want to read a file, less command is a far better choice.
less path_to_file

-Using alias to fix typos: You probably already know what is an alias command in Linux. What you can do is, to use them to fix typos.
For example, you might often mistype grep as gerp. If you put an alias in your bashrc in this fashion:

alias gerp=grep

-Using yes command for commands or scripts that need interactive response: If there are some commands or scripts that need user interaction and you know that you have to enter Y each time it requires an input, you can use Yes command. Just use it in the below fashion:

yes | command_or_script

-Empty a file without deleting it: If you just want to empty the contents of a text file without deleting the file itself, you can use a command similar to this:

> filename

-Find if there are files containing a particular text: There are multiple ways to search and find in Linux command line. But in the case when you just want to see if there are files that contain a particular text, you can use this command:

grep -Pri Search_Term path_to_directory

-Using help with any command: I’ll conclude this article with one more obvious and yet very important ‘trick’, using help with a command or a command line tool. Almost all command and command line tool come with a help page that shows how to use the command. Often using help will tell you the basic usage of the tool/command. Just use it in this fashion:

command_tool --help

-The “uname” command stands for (Unix Name), print detailed information about the machine name, Operating System and Kernel.

-chown: The Linux “chown” command stands for (change file owner and group). Every file belongs to a group of user and a owner. It is used Do ‘ls -l‘ into your directory and you will see something like this.

-Service command is used to run the system V init scripts. i.e Instead of calling the scripts located in the /etc/init.d/ directory with their full path, you can use the service command.

Check the status of a service:

service ssh status

- Use ifconfig command to view or configure a network interface on the Linux system.

View all the interfaces along with status.

$ ifconfig -a


### 3




## Referencias  


