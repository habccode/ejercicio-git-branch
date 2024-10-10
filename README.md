# ejercicio-git-branch

## Clonacion de Repositorio.

```java\code\console o bash
 Code Terminal.
Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets (main|MERGING)
$ git clone https://github.com/habccode/ejercicio-git-branch.git
Cloning into 'ejercicio-git-branch'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.


```


##  Creacion de la rama.
```
### 

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets (main|MERGING)
$ cd ejercicio
ejercicio/            ejercicio-git-branch/

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets (main|MERGING)
$ cd ejercicio-git-branch/

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets/ejercicio-git-branch (main)
$ pwd
/c/Users/Usuario/Documents/tarea_ciclo/ets/ejercicio-git-branch

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets/ejercicio-git-branch (main)
$     git checkout -b ejercicio1-branch
Switched to a new branch 'ejercicio1-branch'

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets/ejercicio-git-branch (ejercicio1-branch)
$ code .


```


### Subir los commit y actualizaciones.
```
Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets/ejercicio-git-branch (ejercicio1-branch)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets/ejercicio-git-branch (main)
$ git merge ejercicio1-branch
Updating 7163bcf..5572a81
Fast-forward
 README.md       | 43 ++++++++++++++++++++++++++++++++++++++++++-
 ejercicio1.java |  5 +++++
 2 files changed, 47 insertions(+), 1 deletion(-)
 create mode 100644 ejercicio1.java

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets/ejercicio-git-branch (main)
$ git add .

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets/ejercicio-git-branch (main)
$ git commit -m"merge_rama_tabla"
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets/ejercicio-git-branch (main)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/habccode/ejercicio-git-branch.git
   7163bcf..5572a81  main -> main

Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets/ejercicio-git-branch (main)
$

```