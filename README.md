# Evaluacion13DeAgostoGitGitHub

> la diferencias son que cd... = navegacion hacia atras y cd = es para ingresar ala carpeta
como lo aclara su definicion el cd.. cuando estoy en una carpeta y necesito devolverme y el cd para ingresar a la carpeta deseada.  

>  2=  mkdir = crear una carpeta del directo 

> touch = crear blok de texto 

> pwd = se utiliza para mostrar directorio actual

> ls -all = muestra toda la lista de archivos 

> ls = se utiliza para listar los archivos 

# El primer paso es configurar el nombre de usuario.
> Configurar el nombre de usuario

git config --global user.name "Nombre de Usuario"

# El segundo paso es configurar el correo electrónico.
> Configurar el correo electrónico

git config --global user.email correo@correo.com
Recomiendo cambiar la rama principal de `master` a `main`.

# Cambiar el nombre de la rama principal
git config --global init.defaultBranch main

# Verificar la configuración realizada.
> Verificar la configuración realizada
git config --list

> 4 = git add .

> git commit -m "first commit"

> git push -u origin main 

# que es un pull request
> Un pull request es una petición que el propietario de un fork de un repositorio hace al propietario del repositorio original para que este último incorpore los commits que están en el fork. En el caso que nos ocupa, el usuario aprendegit-user1 le enviará la petición a aalbagarcia para que este último incorpore los commits que tiene en su fork.

 $ git checkout mycommits
git push -u origin mycommits
Total 0 (delta 0), reused 0 (delta 0)
To git@github-aprendegit-user1:aprendegit-user1/fork
* [new branch] mycommits -> mycommits
Branch mycommits set up to track remote branch mycommits from origin.
