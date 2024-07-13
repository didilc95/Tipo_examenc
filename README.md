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

* [ ] Crea un nuevo repositorio en GitHub
* [ ] Clona el repositorio a tu máquina local
* [ ] Crea un nuevo archivo, hazle commit y súbelo al repositorio remoto
* [ ] Modifica el archivo desde la interfaz web de GitHub
* [ ] Descarga los cambios a tu repositorio local
* [ ] Resuelve el conflicto si lo hay

  Comandos a utilizar: git clone, git add, git commit, git push, git pull

# 3- Etiquetado de versiones

Objetivo: Practicar la creación y gestión de tags.

Pasos:

* [ ] En tu repositorio local, crea un tag ligero llamado "v1.0" en el último commit
* [ ] Crea un tag anotado llamado "v1.1" con un mensaje
* [ ] Sube ambos tags al repositorio remoto
* [ ] Elimina el tag "v1.0" localmente y en el remoto
  
  Comandos a utilizar: git tag, git tag -a, git push --tags, git tag -d, git push origin --delete

# 4- Navegación en el historial y modificación de commits

Objetivo: Practicar la navegación entre commits y la modificación del historial.

Pasos:

* [ ] Revisa el log de commits y copia el hash de un commit anterior
* [ ] Navega a ese commit anterior
* [ ] Crea una nueva rama desde ese punto llamada "hotfix"
* [ ] Realiza un cambio, haz commit y vuelve a master
* [ ] Usa cherry-pick para traer ese commit a master
* [ ] Modifica el mensaje del último commit

  Comandos a utilizar: git log, git checkout, git branch, git cherry-pick, git commit --amend
