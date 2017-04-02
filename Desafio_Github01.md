Last login: Fri Mar 31 21:10:56 on console
MacBook-Pro-Andrea-Vela:~ Velisima$ ls
Adlm			Dropbox (Anterior)	Public
Applications		Google Drive		archivo_pruebasudo.txt
DesafioCodes		Library			id_rsa
Desktop			Maxwell			id_rsa.pub
Documents		Movies			workspace
Downloads		Music
Dropbox			Pictures
MacBook-Pro-Andrea-Vela:~ Velisima$ Documents
-bash: Documents: command not found
MacBook-Pro-Andrea-Vela:~ Velisima$ cd Documents
MacBook-Pro-Andrea-Vela:Documents Velisima$ ls
AMBROSÍA
ANTEPROYECTO-ZIH.skp
ANTEPROYECTO-ZIH~.skp
Adios Amor.docx
AutoCAD Projects
Autodesk
BACALAO
DISEÑO MUEBLES.dwg
Datos de usuario de Microsoft
IVYA 2016
LECTURAS MARZO 2017
La miseria es un platillo amargo que entumece.docx
MOBILIARIO 1.pptx
Paginas web 2017
TZOLKIN 
Ya que no hemos podido hablar.docx
desafio_latam
hardcopy.log
memes
plot.log
testfolder
MacBook-Pro-Andrea-Vela:Documents Velisima$ cd desafio_latam
MacBook-Pro-Andrea-Vela:desafio_latam Velisima$ ls
CSS					TEMA 2 3 4.rtf
Desafios				TEMA 3 GIT.rtf
Diapositivas				carpetaI
Diapositivas-20170311T152054Z-001.zip	carpetaII
HTML PAGINA WEB				index.html
PROGRAMAS Y APLICACIONES
MacBook-Pro-Andrea-Vela:desafio_latam Velisima$ cd Desafios
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	DesafioGithub.md
Desafio01				gitprueba
Desafio02				sudoarchive.txt
Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ nano Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cd DesafioGithub.md
-bash: cd: DesafioGithub.md: Not a directory
MacBook-Pro-Andrea-Vela:Desafios Velisima$ nano DesafioGithub.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cd ..
MacBook-Pro-Andrea-Vela:desafio_latam Velisima$ ls
CSS					TEMA 2 3 4.rtf
Desafios				TEMA 3 GIT.rtf
Diapositivas				carpetaI
Diapositivas-20170311T152054Z-001.zip	carpetaII
HTML PAGINA WEB				index.html
PROGRAMAS Y APLICACIONES
MacBook-Pro-Andrea-Vela:desafio_latam Velisima$ cd carpetaI
MacBook-Pro-Andrea-Vela:carpetaI Velisima$ ls
Readme.md
MacBook-Pro-Andrea-Vela:carpetaI Velisima$ nano Readme.md
MacBook-Pro-Andrea-Vela:carpetaI Velisima$ cd ..
MacBook-Pro-Andrea-Vela:desafio_latam Velisima$ ls
CSS					TEMA 2 3 4.rtf
Desafios				TEMA 3 GIT.rtf
Diapositivas				carpetaI
Diapositivas-20170311T152054Z-001.zip	carpetaII
HTML PAGINA WEB				index.html
PROGRAMAS Y APLICACIONES
MacBook-Pro-Andrea-Vela:desafio_latam Velisima$ cd Desafios
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	DesafioGithub.md
Desafio01				gitprueba
Desafio02				sudoarchive.txt
Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ rm DesafioGithub.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio03.md
Desafio01				gitprueba
Desafio02				sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ touch Desafio_Github01.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio_Github01.md
Desafio01				gitprueba
Desafio02				sudoarchive.txt
Desafio03.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ mkdir carpeta1
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git init
Initialized empty Git repository in /Users/usuario/Documents/desafio_latam/Desafios/.git/
MacBook-Pro-Andrea-Vela:Desafios Velisima$ touch Readme.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ nano Readme.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cat Read.me
cat: Read.me: No such file or directory
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cad Read.me
-bash: cad: command not found
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cat Read.me
cat: Read.me: No such file or directory
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Readme.md
Desafio01				carpeta1
Desafio02				gitprueba
Desafio03.md				sudoarchive.txt
Desafio_Github01.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ mv Readme.md carpeta1
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio_Github01.md
Desafio01				carpeta1
Desafio02				gitprueba
Desafio03.md				sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cd carpeta1
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ ls
Readme.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ ls -la
total 8
drwxr-xr-x   3 Velisima  staff  102 Mar 31 22:19 .
drwxr-xr-x  11 Velisima  staff  374 Mar 31 22:19 ..
-rw-r--r--   1 Velisima  staff    7 Mar 31 22:15 Readme.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git init
Initialized empty Git repository in /Users/usuario/Documents/desafio_latam/Desafios/carpeta1/.git/
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ ls
Readme.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ ls -la
total 8
drwxr-xr-x   4 Velisima  staff  136 Mar 31 22:22 .
drwxr-xr-x  11 Velisima  staff  374 Mar 31 22:19 ..
drwxr-xr-x  10 Velisima  staff  340 Mar 31 22:22 .git
-rw-r--r--   1 Velisima  staff    7 Mar 31 22:15 Readme.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git add Readme.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   Readme.md

MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git commit -m "Primer texto en desafio"
[master (root-commit) 3890e78] Primer texto en desafio
 1 file changed, 2 insertions(+)
 create mode 100644 Readme.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git remote add origin https://github.com/andreavela266/DesafioGithub01.git
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git push -u origin master
Counting objects: 3, done.
Writing objects: 100% (3/3), 229 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/andreavela266/DesafioGithub01.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git push Readme.md
fatal: Invalid gitfile format: Readme.md
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git remote add origin https://github.com/andreavela266/DesafioGithub01.git
fatal: remote origin already exists.
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git push -u origin masterhttps://github.com/andreavela266/DesafioGithub01.git
fatal: remote part of refspec is not a valid name in masterhttps://github.com/andreavela266/DesafioGithub01.git
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git add Readme.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git commit -m "Primer texto"
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git push --all
Everything up-to-date
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ 

