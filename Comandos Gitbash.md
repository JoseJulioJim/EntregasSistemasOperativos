# Comandos y comodines GitBash

## Comandos

- pwd: este comando te escribe el directorio en el cual estás trabajando.
~~~
Rojo17@Rojo17 MINGW64 ~
$ pwd
/c/Users/Rojo17
~~~

- whoami: este comando sirve para poder visualizar quién es el autor del archivo.
~~~
Rojo17@Rojo17 MINGW64 ~
$ whoami
Rojo17
~~~

- help o -- help: muestra todos los comandos disponibles en el GitBash.
~~~
Rojo17@Rojo17 MINGW64 ~
$ help
GNU bash, version 5.1.16(1)-release (x86_64-pc-msys)
These shell commands are defined internally.  Type `help' to see this list.
Type `help name' to find out more about the function `name'.
~~~
etc
- clear: Elimina todo el código que se encuentra escrito en el GitBash.
~~~
Verde16@Verde16 MINGW64 ~
$ clear
~~~
**procede a borrar todo**

- ls: te muestra todas las carpetas que hay en una ubicación.
~~~
Rojo17@Rojo17 MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Configuración local'@
 Contacts/
 Cookies@
'Datos de programa'@
 Desktop/
 Documents/
 Downloads/
'Entorno de red'@
 Favorites/
 Impresoras@
'Jose Julio'/
 Links/
'Menú Inicio'@
'Mis documentos'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 OneDrive/
 Pictures/
 Plantillas@
'Proyecto semestral'/
 Reciente@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 source/
~~~

- cd: este te permite cambiar de lugar el directorio donde estás trabajando.

~~~
Rojo17@Rojo17 MINGW64 ~
$ cd noexisteaqui
~~~

- touch: te permite crear un archivo nuevo.
~~~
Rojo17@Rojo17 MINGW64 ~
$ touch awa
~~~
**se crea un archivo nuevo**

- echo: te permite crear un archivo con contenido dentro de el.

~~~
Rojo17@Rojo17 MINGW64 ~
$ echo dameawa
dameawa
~~~

- cat: Ubica el texto del archivo en la terminal.
~~~
Rojo17@Rojo17 MINGW64 ~
$ cat dameawa
cat: dameawa: No such file or directory
~~~
**busco el archivo y no lo encontro**
- mkdir: te permite crear un nuevo directorio.
~~~
Rojo17@Rojo17 MINGW64 ~
$ mkdir prueba
~~~
**Se creo un directorio llamado prueba**

- rmdir: te permite el  eliminar un direccionario.
~~~
Rojo17@Rojo17 MINGW64 ~
$ rmdir prueba
~~~
**Elimino el direccionario**
- rm: te permite elminar archivos del repositorio.
~~~
Rojo17@Rojo17 MINGW64 ~
$ rm awa
~~~
**Elimino el archivo**

- cp: funciona para copiar de un archivo a otro cierta información.

~~~
Rojo17@Rojo17 MINGW64 ~
$ cp ejemplo

~~~
- mv: te permite mover un archivo de un lugar a otro.
~~~
Rojo17@Rojo17 MINGW64 ~
$ mv ejemplo
~~~

- find: te permite buscar la localización de los archivos.
~~~
Rojo17@Rojo17 MINGW64 ~
$ find
./Proyecto semestral/Library/PackageCache/com.unity.timeline@1.7.1/Samples~/GameplaySequenceDemo/Readme.asset.meta
./Proyecto semestral/Library/PackageCache/com.unity.timeline@1.7.1/Samples~/GameplaySequenceDemo/Scenes
~~~
- code: Abre el visual studio.

~~~
Rojo17@Rojo17 MINGW64 ~
$ code
~~~
**Se creo una nueva ventana de VS Code**

## Comodines

-  (~): te da la dirección para trabajar en el directorio principal.
-  (/): representa el primer directorio en la jerarquia.
-  (.): te marca el directorio actual.
-  (..): es el representante del directorio padre el cual esta un nivel arriba.
-  (-): te regresa al directorio anterior.
-  (""): esto se usa para poner nombres de archivos los cuales tienen espacios en su nombre.