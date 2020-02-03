# Linux_Comandos
Ejercicio de comandos en la consola de linux.

  1.Listar todos los archivos del directorio bin.
    ls /bin
    
  2.Listar todos los archivos del directorio tmp.
    ls /tmp
    
  3.Listar todos los archivos del directorio etc que empiecen por t en orden inverso.
    ls –r /etc/t*
  
  4.Listar todos los archivos del directorio dev que empiecen por tty y tengan 5 caracteres.
    ls /dev/tty??
    
  5.Listar todos los archivos del directorio dev que empiecen por tty y acaben en 1,2,3 ó 4.
    ls /dev/tty*[1-4]
    
  6.Listar todos los archivos del directorio dev que empiecen por t y acaben en C1.
    ls /dev/t*c1

  7.Listar todos los archivos, incluidos los ocultos, del directorio raíz.
    ls –a /
    
  8.Listar todos los archivos del directorio etc que no empiecen por t.
    ls –d /etc/[^t]*

  9.Listar todos los archivos del directorio usr y sus subdirectorios.
  
  10.Cambiarse al directorio tmp, crear directorio PRUEBA.

  11.Verificar que el directorio actual ha cambiado.

  12.Mostrar el día y la hora actual.
  
  13.Con un solo comando posicionarse en el directorio $HOME.
  
  14.Verificar que se está en él.
  
  15.Listar todos los ficheros del directorio HOME mostrando su número de inodo.

  16.Borrar todos los archivos y directorios visibles de vuestro directorio PRUEBA.

  17.Crear los directorios dir1, dir2 y dir3 en el directorio PRUEBA. Dentro de dir1 crear el directorio dir11. Dentro del directorio 
 
  18.dir3 crear el directorio dir31. Dentro del directorio dir31, crear los directorios dir311 y dir312.

  19.Copiar el archivo /etc/motd a un archivo llamado mensaje de vuestro directorio PRUEBA.

  20.Copiar mensaje en dir1, dir2 y dir3.

  21.Comprobar el ejercicio anterior mediante un solo comando.

  22.Copiar los archivos del directorio rc.d que se encuentra en /etc al directorio dir31.
Copiar en el directorio dir311 los archivos de /bin que tengan una a como segunda letra y su nombre tenga cuatro letras.
Copiar el directorio de otro usuario y sus subdirectorios debajo de dir11 (incluido el propio directorio).
Mover el directorio dir31 y sus subdirectorios debajo de dir2.
Mostrar por pantalla los archivos ordinarios del directorio HOME y sus subdirectorios.
Ocultar el archivo mensaje del directorio dir3.
Borrar los archivos y directorios de dir1, incluido el propio directorio.
Copiar al directorio dir312 los ficheros del directorio /dev que empiecen por t, acaben en una letra que vaya de la a a la b y tengan cinco letras en su nombre.
Borrar los archivos de dir312 que no acaben en b y tengan una q como cuarta letra.
Mover el directorio dir312 debajo de dir3.
Crear un enlace simbólico al directorio dir1 dentro del directorio dir3 llamado enlacedir1.
Posicionarse en dir3 y, empleando el enlace creado en el ejercicio anterior, crear el directorio nuevo1 dentro de dir1.
Utilizando el enlace creado copiar los archivos que empiecen por u del directorio /bin en directorio nuevo1.
Crear dos enlaces duros del fichero fich1, llamarlo enlace, en los directorios dir1 y dir2.
Borrar el archivo fich1 y copiar enlace en dir3.
Crear un enlace simbólico (llamado enlafich1) al fichero enlace de dir2 en dir1.
Posicionarse en dir1 y, mediante el enlace creado, copiar el archivo fichl dentro de dir311.
Seguir en dir1 y, mediante el enlace creado, sacar por pantalla las líneas que tiene el archivo fich1.
Borrar el fichero fich1 de dir2.
Borrar todos los archivos y directorios creados durante los ejercicios.
Crear el directorio dir2 y dir3 en el directorio PRUEBA ¿Cuáles son los actuales permisos del directorio dir2?
Utilizando la notación simbólica, eliminar todos los permisos de escritura (propietario, grupo, otros) del directorio dir2.
Utilizando la notación octal, eliminar el permiso de lectura del directorio dir2, al resto de los usuarios.
¿Cuáles son ahora los permisos asociados a dir2?
Crear bajo dir2, un directorio llamado dir2l.
Concederse a sí mismo permiso de escritura en el directorio dir2 e intentar de nuevo el paso anterior.
¿Cuáles son los valores por omisión asignados a los archivos?
Cambiar el directorio actual al directorio dir3. Imprimir su trayectoria completa para verificar el cambio.
¿Cuáles son los permisos asignados en su momento a este directorio?
Reiniciar el ordenador.
Crear cuatro nuevos directorios llamados dira, dirb, dirc, y dird bajo el directorio actual.
Comprobar los permisos de acceso de los directorios recién creados para comprobar el funcionamiento del comando umask.
Crear el fichero uno . Quitarle todos los permisos de lectura. Comprobarlo. Intentar borrar dicho fichero.
Quitarle todos los permisos de paso al directorio dir2 y otorgarle todos los demás.
Crear en el directorio propio:
El directorio carpeta1 con los tres permisos para el propietario, dentro de él fich1 con lectura y escritura para todos y fich2 con lectura y escritura para el propietario y solo lectura para el resto. El directorio carpeta2 con todos los permisos para el propietario y lectura y ejecución para los del mismo grupo. Dentro file1 con lectura y escritura para el propietario y los del grupo y file2 con los mismos para el propietario y solo lectura para el grupo.
Desde otro usuario probar todas las operaciones que se pueden hacer en los ficheros y directorios creados.
Visualizar la trayectoria completa del directorio actual. Crear dos directorios llamados correo y fuentes debajo del directorio actual.
Posicionarse en el directorio fuentes y crear los directorios dir1, dir2, dir3.
Crear el directorio menus bajo correo sin moverse del directorio actual.
Posicionarse en el directorio HOME. Borrar los directorios que cuelgan de fuentes que acaben en un número que no sea el 1.
Ver si existe el archivo tty2 en el directorio dev. En caso de que exista, ver su fecha de creación o actualización.
Ver los permisos que tienen los archivos que empiecen por tt del directorio /dev.
Visualizar la lista de los archivos ordinarios que están en el directorio /usr/bin.

  
    
