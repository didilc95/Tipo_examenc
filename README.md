# 1- Creación y navegación de ramas

Objetivo: Practicar la creación de ramas, cambio entre ellas y fusión.

Pasos:

* [ ] Crea un nuevo repositorio con git init
* [ ] Crea un archivo README.md y haz el commit inicial
* [ ] Crea una nueva rama llamada "feature-1"
* [ ] Cambia a la rama "feature-1"
* [ ] Modifica README.md y haz un commit con mensaje "añadiendo rama feature-1"
* [ ] Vuelve a la rama master
* [ ] Fusiona "feature-1" en master
* [ ] Elimina la rama "feature-1"

  Comandos a utilizar: git init, git add, git commit, git branch, git checkout, git merge, git branch -d

# 2- Trabajo con repositorios remotos

Objetivo: Practicar la interacción con repositorios remotos.
Pasos:
a) Crea un nuevo repositorio en GitHub
b) Clona el repositorio a tu máquina local
c) Crea un nuevo archivo, hazle commit y súbelo al repositorio remoto
d) Modifica el archivo desde la interfaz web de GitHub
e) Descarga los cambios a tu repositorio local
f) Resuelve el conflicto si lo hay
Comandos a utilizar: git clone, git add, git commit, git push, git pull

# 3- Etiquetado de versiones

Objetivo: Practicar la creación y gestión de tags.
Pasos:
a) En tu repositorio local, crea un tag ligero llamado "v1.0" en el último commit
b) Crea un tag anotado llamado "v1.1" con un mensaje
c) Sube ambos tags al repositorio remoto
d) Elimina el tag "v1.0" localmente y en el remoto
Comandos a utilizar: git tag, git tag -a, git push --tags, git tag -d, git push origin --delete

# 4- Navegación en el historial y modificación de commits

Objetivo: Practicar la navegación entre commits y la modificación del historial.
Pasos:
a) Revisa el log de commits y copia el hash de un commit anterior
b) Navega a ese commit anterior
c) Crea una nueva rama desde ese punto llamada "hotfix"
d) Realiza un cambio, haz commit y vuelve a master
e) Usa cherry-pick para traer ese commit a master
f) Modifica el mensaje del último commit
Comandos a utilizar: git log, git checkout, git branch, git cherry-pick, git commit --amend
