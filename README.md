Configuracion Inicial 

Git global setup

git config --global user.name "Nidia Karina  Garzon "
git config --global user.email "nkarinag@hotmail.com"
Create a new repository
git clone https://gitlab.com/mintic2021-s37-grupo-8/pruebaspring3.git
cd pruebaspring3
git switch -c main
touch README.md
git add README.md
git commit -m "add README"
git push -u origin main
Push an existing folder
cd existing_folder
git init --initial-branch=main
git remote add origin https://gitlab.com/mintic2021-s37-grupo-8/pruebaspring3.git
git add .
git commit -m "Initial commit"
git push -u origin main
Push an existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.com/mintic2021-s37-grupo-8/pruebaspring3.git
git push -u origin --all
git push -u origin --tags

Agregar contenido al proyecto 
Agregar mas información al proyecto 
Agregar contenido al proyecto 
Agregar mas información al proyecto Agregar contenido al proyecto 
Agregar mas información al proyecto 
ok
