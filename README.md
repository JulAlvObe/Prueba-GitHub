# Prueba-GitHub
Aprendiendo GitHub:

www.github.com  (nos loggeamos)
-your repositories
-new
-nombramos el repostorio <name>
-Description
* Public (or *Private)
-Add a README file
-CREATE REPOSITORY
-CODE
-Clonamos el archivo creado (https://...)
------------------------------------------
-Vamos al escritorio 
-Abrimos el Git Bash (directorio de trabajo:~\Desktop)
$ git clone <link clonado>      --> lo convierte en carpeta sobre \Desktop
$ cd <nombre del file creado>/
$ code .                    --> se abre el VSCode conteniendo la carpeta clonada
------------------------------------------
-abrimos el archivo, en este caso README.md y modificamos el contenido
-guardamos los cambios
------------------------------------------
$ git add README.md
$ git commit -m "commit de prueba"
$ git push origin main      --> envia nuestro repositorio local modificado a nuestro repositorio en GitHub
------------------------------------------

-Volvemos al repositorio en GitHub
-Actualizamos pagina        --> vemos los cambios realizados
===============================================================
===============================================================
Para enviar un archivo existente a repositorio en GitHub
Creamos un repositorio vacio:

www.github.com  (nos loggeamos)
-your repositories
-new
-nombramos el repostorio <name>
-Description
* Public (or *Private)
-NO: Add a README file
-CREATE REPOSITORY
-Copiamos la direccion creada (https://...) --> no se considera un repositorio porque no tiene ningun archivo

lo probamos con nuestro repositorio local 
-------------------------------------------
$ cd PreCourse\ Henry/
$ git remote add origin http://...  insertando el nombre del archivo
$ git branch -M main        -->aqui puedes modificar el nombre de rama de trabajo actual
$ git push -u origin main
------------------------------------------
-volvemos al GitHub
-actualizamos bnuestro espacio de trabajo
-observamos el nuevo repositorio
---------------------------------------------