san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP (master)
$ git clone https://github.com/pow3rHR/Parcial-I-syp.git
Cloning into 'Parcial-I-syp'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 9 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), 142.78 KiB | 458.00 KiB/s, done.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP (master)
$ ls
Parcial-I-syp/

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP (master)
$ cd Parcial-I-syp

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git remote add origin https://github.com/Gaby-04/SolucionParcial1SYP.git
error: remote origin already exists.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git remote -v
origin  https://github.com/pow3rHR/Parcial-I-syp.git (fetch)
origin  https://github.com/pow3rHR/Parcial-I-syp.git (push)


san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git remote set-url origin https://github.com/Gaby-04/SolucionParcial1SYP.git

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git remote -v
origin  https://github.com/Gaby-04/SolucionParcial1SYP.git (fetch)
origin  https://github.com/Gaby-04/SolucionParcial1SYP.git (push)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ touch respuestas.txt

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   respuestas.txt


san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git commit -m "Creando archivo de respuesta"
[master be2ed4e] Creando archivo de respuesta
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 respuestas.txt

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git push -u origin master
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (12/12), 143.01 KiB | 71.50 MiB/s, done.
Total 12 (delta 1), reused 8 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Gaby-04/SolucionParcial1SYP.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git commit -m "Agregando respuesta 1"
[master b996721] Agregando respuesta 1
 1 file changed, 3 insertions(+)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git commit -m "Agregando respuesta 2"
[master 16e9daa] Agregando respuesta 2
 1 file changed, 14 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
commit 16e9daa92320e4c70279e0ae433731e6859887f3 (HEAD -> master)
Author: Katherine <katherineamaya2200@gmail.com>
Date:   Thu Apr 8 21:11:59 2021 -0600

    Agregando respuesta 2

commit b996721520f1192ec33e03cc87796c12f1a8902f
Author: Katherine <katherineamaya2200@gmail.com>
Date:   Thu Apr 8 21:10:19 2021 -0600

    Agregando respuesta 1

commit be2ed4e0a5584fd8296821140ea5b8c5df66a458 (origin/master, origin/HEAD)
Author: Katherine <katherineamaya2200@gmail.com>
Date:   Thu Apr 8 20:55:36 2021 -0600

    Creando archivo de respuesta

commit 31771d828d47549de4785f6ecc1303d5b7276653
Author: pow3rHR <80113305+pow3rHR@users.noreply.github.com>
Date:   Thu Mar 25 09:26:54 2021 -0600

    Update README.md

commit 08ea418a8e211a88e3b11d5627c521e3ac9974ba
Author: pow3rHR <80113305+pow3rHR@users.noreply.github.com>
Date:   Thu Mar 25 09:26:20 2021 -0600

    Create README.md

commit 3007242195d6324df48f3c837e5884ccf3db5eab
Author: = <=>
Date:   Thu Mar 18 09:22:01 2021 -0600

    Parcial I syp 2021
~
~
~
~
~
~
~
~
~
~
~
~
~

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git commit -m "Agregando respuesta 3"
[master 25777fb] Agregando respuesta 3
 1 file changed, 7 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git commit -m "Agregando respuesta 4"
[master 8d1c451] Agregando respuesta 4
 1 file changed, 3 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git commit -m "Agregando pregunta 5"
[master d8ea7c8] Agregando pregunta 5
 1 file changed, 10 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git push -u origin master
Enumerating objects: 17, done.
Counting objects: 100% (17/17), done.
Delta compression using up to 4 threads
Compressing objects: 100% (15/15), done.
Writing objects: 100% (15/15), 1.94 KiB | 995.00 KiB/s, done.
Total 15 (delta 9), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (9/9), completed with 1 local object.
To https://github.com/Gaby-04/SolucionParcial1SYP.git
   be2ed4e..d8ea7c8  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git branch rama2

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git branch
* master
  rama2

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (master)
$ git checkout rama2
Switched to branch 'rama2'

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git branch
  master
* rama2

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git commit -m "Agregando respuesta 6"
[rama2 1492b3d] Agregando respuesta 6
 1 file changed, 24 insertions(+)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git commit -m "Agregando respuesta 7"
[rama2 e5defd9] Agregando respuesta 7
 1 file changed, 6 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git commit -m "Agregando pregunta 8"
[rama2 f467753] Agregando pregunta 8
 1 file changed, 14 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git commit -m "Agregando respuesta 9"
[rama2 346b487] Agregando respuesta 9
 1 file changed, 8 insertions(+)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git add .

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git commit -m "Agregando respuesta 10"
[rama2 cd32117] Agregando respuesta 10
 1 file changed, 3 insertions(+), 1 deletion(-)

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$ git push -u origin rama2
Enumerating objects: 17, done.
Counting objects: 100% (17/17), done.
Delta compression using up to 4 threads
Compressing objects: 100% (15/15), done.
Writing objects: 100% (15/15), 3.17 KiB | 1.58 MiB/s, done.
Total 15 (delta 9), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (9/9), completed with 1 local object.
remote:
remote: Create a pull request for 'rama2' on GitHub by visiting:
remote:      https://github.com/Gaby-04/SolucionParcial1SYP/pull/new/rama2
remote:
To https://github.com/Gaby-04/SolucionParcial1SYP.git
 * [new branch]      rama2 -> rama2
Branch 'rama2' set up to track remote branch 'rama2' from 'origin'.

san miguel@KATHERINE-SANCHEZ MINGW64 ~/Desktop/SolucionParcial1SYP/Parcial-I-syp (rama2)
$

