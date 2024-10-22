# ejercicio-git-branch
````
public class Ejercicio1 {
    public static void main(String[] args) {
        System.out.println("Ejercicio 1 realizado.");
    }
}  

````
   
   ##

   ## Clonamos nuestro repositorio. ##
````

 ls
Github/
Usuario@DESKTOP-5OONOR5 MINGW64 ~/Documents/tarea_ciclo/ets (main|MERGING)
$ git clone https://github.com/habccode/ejercicio-git-branch.git
Cloning into 'ejercicio-git-branch'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.
````
## Buscando los ejercicios para crear la nueva rama ##
  ````        Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents (main|MERGING)
$ cd ets
bash: cd: ets: No such file or directory

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents (main|MERGING)
$ cd tarea_ciclo

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo (main|MERGING)
$ cd ets

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets (main|MERGING)
$ ls
Github/  ejercicio-git-branch/

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets (main|MERGING)
$ cd ejercicio-git-branch/

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets/ejercicio-git-branch (ejercicio1-branch)
$ ls
Ejercicio1.java  README.md
  ```` 

## Creacion de la rama2 ##                   
            
````Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents (main|MERGING)
$ cd ets
bash: cd: ets: No such file or directory

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents (main|MERGING)
$ cd tarea_ciclo

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo (main|MERGING)
$ cd ets

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets (main|MERGING)
$ ls
Github/  ejercicio-git-branch/

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets (main|MERGING)
$ cd ejercicio-git-branch/

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets/ejercicio-git-branch (ejercicio1-branch)
$ ls
Ejercicio1.java  README.md

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets/ejercicio-git-branch (ejercicio1-branch)
$ git branch
* ejercicio1-branch
  main

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets/ejercicio-git-branch (ejercicio1-branch)
$     git checkout -b ejercicio2-branch
Switched to a new branch 'ejercicio2-branch'

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets/ejercicio-git-branch (ejercicio2-branch)
$ git branch
  ejercicio1-branch
* ejercicio2-branch
  main

Usuario@DESKTOP-5OONOR5 MINGW64 ~/documents/tarea_ciclo/ets/ejercicio-git-branch (ejercicio2-branch)
$     git checkout  ejercicio2-branch
Already on 'ejercicio2-branch'
M       Ejercicio1.java
M       README.md


````
   
    

