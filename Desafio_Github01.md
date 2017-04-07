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

Last login: Sat Apr  1 19:29:16 on console
MacBook-Pro-Andrea-Vela:~ Velisima$ ls
Adlm			Dropbox (Anterior)	Public
Applications		Google Drive		archivo_pruebasudo.txt
DesafioCodes		Library			id_rsa
Desktop			Maxwell			id_rsa.pub
Documents		Movies			workspace
Downloads		Music
Dropbox			Pictures
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
Desafio identificacion de permisos.md	Desafio_Github01.md
Desafio01				carpeta1
Desafio02				gitprueba
Desafio03.md				sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -la
total 48
drwxr-xr-x  11 Velisima  staff   374 Mar 31 22:19 .
drwxr-xr-x  14 Velisima  staff   476 Mar 25 09:42 ..
drwxr-xr-x  10 Velisima  staff   340 Mar 31 22:13 .git
-rw-r--r--   1 Velisima  staff  8292 Mar 16 01:12 Desafio identificacion de permisos.md
-rw-r--r--   1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--   1 Velisima  staff     0 Mar 16 00:13 Desafio02
-rw-------   1 Velisima  staff     1 Mar 31 22:02 Desafio03.md
-rw-r--r--   1 Velisima  staff  7044 Apr  1 09:19 Desafio_Github01.md
drwxr-xr-x   4 Velisima  staff   136 Mar 31 22:22 carpeta1
drwxr-xr-x   5 Velisima  staff   170 Mar 27 23:17 gitprueba
-rw-------   1 Velisima  staff     0 Mar 16 01:07 sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	Desafio identificacion de permisos.md
	Desafio01
	Desafio02
	Desafio03.md
	Desafio_Github01.md
	carpeta1/
	gitprueba/
	sudoarchive.txt

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git add --all
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   Desafio identificacion de permisos.md
	new file:   Desafio01
	new file:   Desafio02
	new file:   Desafio03.md
	new file:   Desafio_Github01.md
	new file:   carpeta1
	new file:   gitprueba/Gitdesafio02.md
	new file:   gitprueba/hola.txt
	new file:   sudoarchive.txt

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git commit -m "Desafios Github clases 02-03"
[master (root-commit) 215915f] Desafios Github clases 02-03
 9 files changed, 436 insertions(+)
 create mode 100644 Desafio identificacion de permisos.md
 create mode 100644 Desafio01
 create mode 100755 Desafio02
 create mode 100644 Desafio03.md
 create mode 100644 Desafio_Github01.md
 create mode 160000 carpeta1
 create mode 100644 gitprueba/Gitdesafio02.md
 create mode 100644 gitprueba/hola.txt
 create mode 100644 sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio_Github01.md
Desafio01				carpeta1
Desafio02				gitprueba
Desafio03.md				sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ touch carpeta2
MacBook-Pro-Andrea-Vela:Desafios Velisima$ mkdir carpeta2
mkdir: carpeta2: File exists
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cd carpeta2
-bash: cd: carpeta2: Not a directory
MacBook-Pro-Andrea-Vela:Desafios Velisima$ rm -ri carpeta2
remove carpeta2? Y
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio_Github01.md
Desafio01				carpeta1
Desafio02				gitprueba
Desafio03.md				sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ mkdir carpeta2
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	carpeta1
Desafio01				carpeta2
Desafio02				gitprueba
Desafio03.md				sudoarchive.txt
Desafio_Github01.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cd carpeta2
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git init
Initialized empty Git repository in /Users/usuario/Documents/desafio_latam/Desafios/carpeta2/.git/
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git status
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git push --all
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>

MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git push https://github.com/andreavela266/DesafioGitHUB.git
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/andreavela266/DesafioGitHUB.git master

MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git push --set-upstream https://github.com/andreavela266/DesafioGitHUB.git master
error: src refspec master does not match any.
error: failed to push some refs to 'https://github.com/andreavela266/DesafioGitHUB.git'
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git status
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git diff HEAD
fatal: ambiguous argument 'HEAD': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git diff master
fatal: ambiguous argument 'master': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git status
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git diff 
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git status
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git fetch origin
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git remote
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git remote origin
error: Unknown subcommand: origin
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand

MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git remote add origin <https://github.com/andreavela266/DesafioGitHUB.git>
-bash: syntax error near unexpected token `newline'
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git remote add origin https://github.com/andreavela266/DesafioGitHUB.git
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ git status
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ ls
MacBook-Pro-Andrea-Vela:carpeta2 Velisima$ cd ..
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	carpeta1
Desafio01				carpeta2
Desafio02				gitprueba
Desafio03.md				sudoarchive.txt
Desafio_Github01.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cd carpeta1
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ ls
Readme.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ nano Read.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ cat Read.md
Hola02
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git add Read.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   Read.md

MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git commit -m "desafio01-github"
[master 0807305] desafio01-github
 1 file changed, 1 insertion(+)
 create mode 100644 Read.md
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git push origin/master
fatal: 'origin/master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git remote
origin
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ git push --all
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 280 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/andreavela266/DesafioGithub01.git
   3890e78..0807305  master -> master
MacBook-Pro-Andrea-Vela:carpeta1 Velisima$ cd ..
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	carpeta1
Desafio01				carpeta2
Desafio02				gitprueba
Desafio03.md				sudoarchive.txt
Desafio_Github01.md
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -la
total 48
drwxr-xr-x  12 Velisima  staff   408 Apr  1 20:18 .
drwxr-xr-x  14 Velisima  staff   476 Mar 25 09:42 ..
drwxr-xr-x  13 Velisima  staff   442 Apr  1 20:11 .git
-rw-r--r--   1 Velisima  staff  8292 Mar 16 01:12 Desafio identificacion de permisos.md
-rw-r--r--   1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--   1 Velisima  staff     0 Mar 16 00:13 Desafio02
-rw-------   1 Velisima  staff     1 Mar 31 22:02 Desafio03.md
-rw-r--r--   1 Velisima  staff  7044 Apr  1 09:19 Desafio_Github01.md
drwxr-xr-x   5 Velisima  staff   170 Apr  1 20:50 carpeta1
drwxr-xr-x   3 Velisima  staff   102 Apr  1 20:18 carpeta2
drwxr-xr-x   5 Velisima  staff   170 Mar 27 23:17 gitprueba
-rw-------   1 Velisima  staff     0 Mar 16 01:07 sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git add --all
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   carpeta1

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote add https://github.com/andreavela266/DesafioGithub01.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=<push|fetch>]
                          set up remote as a mirror to push to or fetch from

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote -f https://github.com/andreavela266/DesafioGithub01.git
error: unknown switch `f'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote set-head DesafioGithub01 https://github.com/andreavela266/DesafioGithub01.git
error: Not a valid ref: refs/remotes/DesafioGithub01/https://github.com/andreavela266/DesafioGithub01.git
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote add origin <remote_repo_url>
-bash: syntax error near unexpected token `newline'
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push --all origingit remote add origin git remote add origin <remote_repo_url>
-bash: syntax error near unexpected token `newline'
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push --all origin
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote add origin https://github.com/andreavela266/DesafioGithub01
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   carpeta1

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push --all
To https://github.com/andreavela266/DesafioGithub01
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/andreavela266/DesafioGithub01'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote -v
origin	https://github.com/andreavela266/DesafioGithub01 (fetch)
origin	https://github.com/andreavela266/DesafioGithub01 (push)
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   carpeta1

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push 
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push --set-upstream origin master
To https://github.com/andreavela266/DesafioGithub01
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/andreavela266/DesafioGithub01'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   carpeta1

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote rm origin
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote add origin https://github.com/andreavela266/DesafioGithub01.git
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   carpeta1

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push origin master
To https://github.com/andreavela266/DesafioGithub01.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/andreavela266/DesafioGithub01.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git pull --all
Fetching origin
warning: no common commits
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://github.com/andreavela266/DesafioGithub01
 * [new branch]      master     -> origin/master
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push https://github.com/andreavela266/DesafioGithub01.git
To https://github.com/andreavela266/DesafioGithub01.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/andreavela266/DesafioGithub01.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git clone https://github.com/andreavela266/DesafioGithub01.git
Cloning into 'DesafioGithub01'...
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio_Github01.md
Desafio01				carpeta1
Desafio02				carpeta2
Desafio03.md				gitprueba
DesafioGithub01				sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ cd DesafioGithub01
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ ls
Read.md		Readme.md
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ pwd
/Users/usuario/Documents/desafio_latam/Desafios/DesafioGithub01
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git ckeckout origin master
git: 'ckeckout' is not a git command. See 'git --help'.

Did you mean this?
	checkout
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ Y
-bash: Y: command not found
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git add DesafioGithub01
fatal: pathspec 'DesafioGithub01' did not match any files
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git add --all
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ ls
Read.md		Readme.md
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git log
commit 08073052cdf4ca9c6d276ca9732295b2d224d18e
Author: Andrea Vela <andreus.vela@gmail.com>
Date:   Sat Apr 1 20:51:25 2017 -0600

    desafio01-github

commit 3890e78b5cf78bb158a964213d54cd741ef89976
Author: Andrea Vela <andreus.vela@gmail.com>
Date:   Fri Mar 31 22:24:52 2017 -0600

    Primer texto en desafio
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git log --summary
commit 08073052cdf4ca9c6d276ca9732295b2d224d18e
Author: Andrea Vela <andreus.vela@gmail.com>
Date:   Sat Apr 1 20:51:25 2017 -0600

    desafio01-github

 create mode 100644 Read.md

commit 3890e78b5cf78bb158a964213d54cd741ef89976
Author: Andrea Vela <andreus.vela@gmail.com>
Date:   Fri Mar 31 22:24:52 2017 -0600

    Primer texto en desafio

 create mode 100644 Readme.md
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git remote add origin https://github.com/andreavela266/mi-primer-repositorio.git
fatal: remote origin already exists.
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ git diff HEAD
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ ls
Read.md		Readme.md
MacBook-Pro-Andrea-Vela:DesafioGithub01 Velisima$ cd ..
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio_Github01.md
Desafio01				carpeta1
Desafio02				carpeta2
Desafio03.md				gitprueba
DesafioGithub01				sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git add --all
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   DesafioGithub01
	modified:   carpeta1

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git commit -m "Subiendo actividades y ejercicios"
[master 894df01] Subiendo actividades y ejercicios
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 160000 DesafioGithub01
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push -u origin master
To https://github.com/andreavela266/DesafioGithub01.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/andreavela266/DesafioGithub01.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push --all
To https://github.com/andreavela266/DesafioGithub01.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/andreavela266/DesafioGithub01.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push DesafioGithub01 https://github.com/andreavela266/mi-primer-repositorio.git
fatal: remote part of refspec is not a valid name in https://github.com/andreavela266/mi-primer-repositorio.git
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git pull -u origin master
error: unknown switch `u'
usage: git pull [<options>] [<repository> [<refspec>...]]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting

Options related to merging
    -r, --rebase[=<false|true|preserve|interactive>]
                          incorporate changes by rebasing rather than merging
    -n                    do not show a diffstat at the end of the merge
    --stat                show a diffstat at the end of the merge
    --log[=<n>]           add (at most <n>) entries from shortlog to merge commit message
    --squash              create a single commit instead of doing a merge
    --commit              perform a commit if the merge succeeds (default)
    --edit                edit message before committing
    --ff                  allow fast-forward
    --ff-only             abort if fast-forward is not possible
    --verify-signatures   verify that the named commit has a valid GPG signature
    --autostash           automatically stash/stash pop before and after rebase
    -s, --strategy <strategy>
                          merge strategy to use
    -X, --strategy-option <option=value>
                          option for selected merge strategy
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    --allow-unrelated-histories
                          allow merging unrelated histories

Options related to fetching
    --all                 fetch from all remotes
    -a, --append          append to .git/FETCH_HEAD instead of overwriting
    --upload-pack <path>  path to upload pack on remote end
    -f, --force           force overwrite of local branch
    -t, --tags            fetch all tags and associated objects
    -p, --prune           prune remote-tracking branches no longer on remote
    --recurse-submodules[=<on-demand>]
                          control recursive fetching of submodules
    -j, --jobs[=<n>]      number of submodules pulled in parallel
    --dry-run             dry run
    -k, --keep            keep downloaded pack
    --depth <depth>       deepen history of shallow clone
    --unshallow           convert to a complete repository
    --update-shallow      accept refs that update .git/shallow
    --refmap <refmap>     specify fetch refmap

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git pull -v
From https://github.com/andreavela266/DesafioGithub01
 = [up to date]      master     -> origin/master
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git pull DesafioGithub01 master
From DesafioGithub01
 * branch            master     -> FETCH_HEAD
fatal: refusing to merge unrelated histories
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push --all
To https://github.com/andreavela266/DesafioGithub01.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/andreavela266/DesafioGithub01.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git diff DesafioGithub01 DesafioGitHUB
fatal: DesafioGitHUB: no such path in the working tree.
Use 'git <command> -- <path>...' to specify paths that do not exist locally.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git diff --https://github.com/andreavela266/DesafioGithub01.git
error: invalid option: --https://github.com/andreavela266/DesafioGithub01.git
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls
Desafio identificacion de permisos.md	Desafio_Github01.md
Desafio01				carpeta1
Desafio02				carpeta2
Desafio03.md				gitprueba
DesafioGithub01				sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ ls -la
total 48
drwxr-xr-x  13 Velisima  staff   442 Apr  1 21:16 .
drwxr-xr-x  14 Velisima  staff   476 Mar 25 09:42 ..
drwxr-xr-x  15 Velisima  staff   510 Apr  1 21:58 .git
-rw-r--r--   1 Velisima  staff  8292 Mar 16 01:12 Desafio identificacion de permisos.md
-rw-r--r--   1 Velisima  staff     0 Mar 15 21:30 Desafio01
-rwxrw-r--   1 Velisima  staff     0 Mar 16 00:13 Desafio02
-rw-------   1 Velisima  staff     1 Mar 31 22:02 Desafio03.md
drwxr-xr-x   5 Velisima  staff   170 Apr  1 21:16 DesafioGithub01
-rw-r--r--   1 Velisima  staff  7044 Apr  1 09:19 Desafio_Github01.md
drwxr-xr-x   5 Velisima  staff   170 Apr  1 20:50 carpeta1
drwxr-xr-x   3 Velisima  staff   102 Apr  1 20:18 carpeta2
drwxr-xr-x   5 Velisima  staff   170 Mar 27 23:17 gitprueba
-rw-------   1 Velisima  staff     0 Mar 16 01:07 sudoarchive.txt
MacBook-Pro-Andrea-Vela:Desafios Velisima$ nano .git
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git add Desafio01
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:Desafios Velisima$ nano Desafio01
MacBook-Pro-Andrea-Vela:Desafios Velisima$ CAT Desafio01
Hola

Soy una prueba
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git add Desafio01
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   Desafio01

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git commit -m "agregando el desafio 01"
[master c02f59c] agregando el desafio 01
 1 file changed, 3 insertions(+)
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git status
On branch master
nothing to commit, working tree clean
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git push --all
To https://github.com/andreavela266/DesafioGithub01.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/andreavela266/DesafioGithub01.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git fetch HEAD
fatal: 'HEAD' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote -f HEAD
error: unknown switch `f'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand

MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote rename DesafioGithub01 Desafio-Latam
fatal: No such remote: DesafioGithub01
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git remote 
origin
MacBook-Pro-Andrea-Vela:Desafios Velisima$ git merge
  [Restaurado]
Last login: Sun Apr  2 16:25:38 on console
MacBook-Pro-Andrea-Vela:Desafios Velisima$ 
