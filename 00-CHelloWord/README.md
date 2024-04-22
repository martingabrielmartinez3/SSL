# SSL
-- Archivo front page del trabajo --
# SSL K2152 2024

# PROCEDIMIENTO
--Para definir la estructura del proyecto se realizaron los siguientes pasos--

1) Desde la terminal CMD se utilizó la siguiente secuencia de comandos:
### a- cd [PATH_ORIGEN] , para ubicar el directorio del proyecto "SSL" en mi computador.
### b- mkdir 00-CHelloWord , para generar el subdirectorio que contendrá los archivos a presentar.
### c- copy [PATH_ORIGEN] [PATH_DESTINO] , donde [PATH_ORIGEN] contiene el archivo "README.md" generado desde GIT. El cual se editó para contener estas aclaraciones.

2) Una vez preparada la estructura y ya dentro del subdirectorio "00-CHelloWord" se generó un archivo.c para desarrollar el código fuente. El mismo se realizó por terminal de la siguiente manera:
### a- copy con hello.c + ENTER
### b- #include <stdio.h> para inicializar el archivo hello.c
### c- CTRL+z para generar el archivo inicializado
### d- Por terminal se mostró el siguiente mensaje: 1 archivo(s) copiado(s).
### e- exit

3) Ya dentro de hello.c se procedió a definir el código fuente.

4) Una vez definido se decidió testear el código para que imprima por pantalla a través de la terminal del VSCode.
### a- CTRL+F5 (Run C File)
### b- Se obtiene por terminal "HELLO WORD"
### c- ya sin errores se avanza hacia el paso "(5)"

5) Para compilar por terminal y generar los archivos hello.exe y hello.txt se realizó la siguiente secuencia de comandos:
### a- CTRL+ c para abrir la terminal CMD desde VSCode, ubicado sobre el directorio del proyecto.
### b- gcc [PATH_ORIGEN]\[hello.c] -o [PATH_DESTINO]\[hello.exe]
### c- cd 00-CHelloWord para avanzar hacia el subdirectorio.
### d- hello.exe > hello.txt , para realizar la redirección con el operador de salida ">" a un archivo de extensión ".txt".
### e- exit

# ENTREGA

6) Finalmente, para comprobar que la estructura sea la correcta se consulta por CMD:
### a- tree [PATH_ORIGEN]\[SSL] para visibilizar la estructura del directorio SSL
### b- tree [PATH_ORIGEN]\[SSL]\[00-CHelloWord] para visibilizar la estructura del directorio 00-CHelloWord
### c- exit
