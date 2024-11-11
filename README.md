Alumno 1: Christian Baizan Ramirez
Alumno 2: Marcos Jimenez Sanchez

HTTPS:https://github.com/Chrisbayy/Evolucion.git

Ejercicio 5:
git config --global user.name “Mi Nombre de usuario de GitHub”
git config --global user.email “Mi correo asignado a GitHub”
git remote add origin [direccionHTTPS]
git remote
git push origin master
git pull prigin master

Ejercicio 7:
Alumno 1:
git checkout -b <ramaAlumno>

Alumno2:
git checkout -b ramaAlno2
git branch -m "ramaAlumno2"

Ejercicio 8:
git branch
El asterisco indica la rama en la que nos encontramos

Ejercicio 9:
Alumno 1:
touch almacen_cli.java
git add .
git commit -m "Añadiendo fichero almacen_clii.java"

Alumno 2:
nano cliente.java
git add cliente.java
git commit -m "Añadiendo fichero cliente.java"

Ejercicio 10:
git diff master ramaAlumno ó git diff master master ramaAlumno2

Ejercicio 11:
Alumno2:
git pull origin master
git merge master ramaAlumno2
git push origin master

Alumno1:
git pull origin master
git config pull.rebase true
git pull origin master
nano README.md
git add README.md
git rebase --continue
git merge master ramaAlumno
git push origin master

Ejercicio 12:
git config --global credential.helper store

Alumno1:
touch LogAlumno1.txt
git add .
git commit -m "prueba credenciales"
git push origin master

Alumno2:
nano LogAlumno2.txt
git add LogAlumno2.txt
git commit -m "Añadido log alumno2"
git push origin master



