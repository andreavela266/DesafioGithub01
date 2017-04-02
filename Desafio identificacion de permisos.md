* Desafio de identifiación de permisos:

drwxr-xr-x = Directorio, usuario: permisos de lectura, escritura y ejecución, 
             grupo: permisos de lectura y ejecución, otro: permisos de lectura
             y ejecución.
-rwxr-xr-x = Archivo, usuario: permisos de lectura, escritura y ejecución, 
             grupo: permisos de lectura y ejecución, otro: permisos de lectura
             y ejecución. 
dr-xrwx-wx = Directorio, usuario: permisos de lectura y ejecución, grupo: 
             permisos de lectura, escritura y ejecución, otros: permisos 
             de escritura y ejecución.
-rw-rw-rw- = Archivo, usuario: lectura y ejecución, grupo: permisos de lectura
             y ejecución, otro: permisos de lectura y ejecución.
-rw-r--r-- = Archivo, usuario: permisos de lectura y ejecución, grupo: permiso
             de lectura, otro: permiso de lectura.
d-w-rwx-w- = Directorio, usuario: permiso de ejecución, grupo: permiso de 
             lectura, escritura y ejecución, otro: permiso de escritura. 

* Desafio de Asignación de permisos

MacBook-Pro-Andrea-Vela:Desafios Velisima$ touch Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio02
Desafio01
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmode u+rw Desafio02
-bash: chmode: command not found
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod u+rw Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 8
-rw-r--r--  1 Velisima  staff  1032 Mar 16 00:07 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rw-r--r--  1 Velisima  staff     0 Mar 16 00:13 Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod g-r o-r Desafio02
chmod: o-r: No such file or directory
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod g-r Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod o-r Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 8
-rw-r--r--  1 Velisima  staff  1032 Mar 16 00:07 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rw-------  1 Velisima  staff     0 Mar 16 00:13 Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod g+rw Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 8
-rw-r--r--  1 Velisima  staff  1032 Mar 16 00:07 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rw-rw----  1 Velisima  staff     0 Mar 16 00:13 Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod u+x Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 8
-rw-r--r--  1 Velisima  staff  1032 Mar 16 00:07 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw----  1 Velisima  staff     0 Mar 16 00:13 Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod o+r Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 8
-rw-r--r--  1 Velisima  staff  1032 Mar 16 00:07 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--  1 Velisima  staff     0 Mar 16 00:13 Desafio02

* DESAFIO

Last login: Wed Mar 15 23:36:37 on ttys002
MacBook-Pro-Andrea-Vela:~ Velisima$ man ls
MacBook-Pro-Andrea-Vela:~ Velisima$ ls
Adlm			Dropbox			Music
Applications		Dropbox (Anterior)	Pictures
DesafioCodes		Google Drive		Public
Desktop			Library			archivo_pruebasudo.txt
Documents		Maxwell			workspace
Downloads		Movies
MacBook-Pro-Andrea-Vela:~ Velisima$ cd Documents
MacBook-Pro-Andrea-Vela:Documents Velisima$ ls
AMBROSÍA
ANTEPROYECTO-ZIH.skp
ANTEPROYECTO-ZIH~.skp
APP VALLY
AutoCAD Projects
Autodesk
BACALAO
DESAFIO LATAM
DISEÑO MUEBLES.dwg
Datos de usuario de Microsoft
IVYA 2016
La miseria es un platillo amargo que entumece.docx
MOBILIARIO 1.pptx
Paginas web 2017
TZOLKIN 
hardcopy.log
memes
plot.log
testfolder
MacBook-Pro-Andrea-Vela:Documents Velisima$ cd ./DESAFIO\ LATAM/
MacBook-Pro-Andrea-Vela:DESAFIO LATAM Velisima$ LS
Desafios				PROGRAMAS Y APLICACIONES
Diapositivas				TEMA 2 3 4.rtf
Diapositivas-20170311T152054Z-001.zip	TEMA 3 GIT.rtf
MacBook-Pro-Andrea-Vela:DESAFIO LATAM Velisima$ cd Desafios
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio02
Desafio01				Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod u+r Desafio.md
chmod: Desafio.md: No such file or directory
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod u+r Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 8
-rw-r--r--  1 Velisima  staff  3129 Mar 16 00:21 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--  1 Velisima  staff     0 Mar 16 00:13 Desafio02
-r--------  1 Velisima  staff     0 Mar 16 00:24 Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ nano Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod u+w Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 8
-rw-r--r--  1 Velisima  staff  3129 Mar 16 00:21 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--  1 Velisima  staff     0 Mar 16 00:13 Desafio02
-rw-------  1 Velisima  staff     0 Mar 16 00:24 Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ 

------ No pude instalar Sublime para abrir el archivo en el


* Desafio con sudo

MacBook-Pro-Andrea-Vela:Desafios Velisima$ sudo touch sudoarchive.txt
Password:
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio03.md
Desafio01				sudoarchive.txt
Desafio02
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 16
-rw-r--r--  1 Velisima  staff  5333 Mar 16 01:06 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--  1 Velisima  staff     0 Mar 16 00:13 Desafio02
-rw-------  1 Velisima  staff     0 Mar 16 00:24 Desafio03.md
-rw-r--r--  1 root      staff     0 Mar 16 01:07 sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ sudo chmod g+w sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ sudo chmod o+w sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 16
-rw-r--r--  1 Velisima  staff  5333 Mar 16 01:06 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--  1 Velisima  staff     0 Mar 16 00:13 Desafio02
-rw-------  1 Velisima  staff     0 Mar 16 00:24 Desafio03.md
-rw-rw-rw-  1 root      staff     0 Mar 16 01:07 sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ sudo chown Velisima sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -l
total 16
-rw-r--r--  1 Velisima  staff  5333 Mar 16 01:06 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--  1 Velisima  staff     0 Mar 16 00:13 Desafio02
-rw-------  1 Velisima  staff     0 Mar 16 00:24 Desafio03.md
-rw-rw-rw-  1 Velisima  staff     0 Mar 16 01:07 sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -la
total 16
drwxr-xr-x  7 Velisima  staff   238 Mar 16 01:07 .
drwxr-xr-x  9 Velisima  staff   306 Mar 15 21:30 ..
-rw-r--r--  1 Velisima  staff  5333 Mar 16 01:06 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--  1 Velisima  staff     0 Mar 16 00:13 Desafio02
-rw-------  1 Velisima  staff     0 Mar 16 00:24 Desafio03.md
-rw-rw-rw-  1 Velisima  staff     0 Mar 16 01:07 sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod g-rw + o-rw sudoarchive.txt
chmod: +: No such file or directory
chmod: o-rw: No such file or directory
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod g-rw sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ chmod o-rw sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -la
total 16
drwxr-xr-x  7 Velisima  staff   238 Mar 16 01:07 .
drwxr-xr-x  9 Velisima  staff   306 Mar 15 21:30 ..
-rw-r--r--  1 Velisima  staff  5333 Mar 16 01:06 Desafio identificacion de permisos.md
-rw-r--r--  1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--  1 Velisima  staff     0 Mar 16 00:13 Desafio02
-rw-------  1 Velisima  staff     0 Mar 16 00:24 Desafio03.md
-rw-------  1 Velisima  staff     0 Mar 16 01:07 sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ 
