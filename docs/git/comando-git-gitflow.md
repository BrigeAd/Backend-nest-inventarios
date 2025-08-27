--Inicializar un nuevo repositorio
git init
-Listar las ramas
git branch 
##Git Flow
git flow init


git add .

git commit -m "Proyecto Base de nest"

-subir a git hub
-Requisitos-1(Crear una cuenta en Github)
-Rquisito-2:Crear un nuevo reepositorio en github
-Asociar git local con el remoto:
git remote add origin url_repo_remoto

-Subir los cambios al repositorio remoto (git hub)
git push origin master
git push origin develop
git checkout master

-Agregar un nuevo feature
git flow feature start add-configuracion

git flow feature finish add-configuracion