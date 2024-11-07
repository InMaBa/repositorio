# Creando un repositorio local
<p>Realizamos el npm install y luego el npm start</p>
<p>Realizamos el git init para empezar el proyecto, y de ahi realizamos un git statos donde veremos lo que no queremos y esos los pondremos en .gitignore
<p> Ponemos git add . para que se apliquen. Donde veremos los archivos que queremos subir en el repositorio
Después del git add ., hacemos el commit inicial
A partir de ese momento, lo subimos en github</p>

 # Subir un el repositorio a github
 <p> Creamos un nuevo repositorio en gitHub, para ello necesitamos el código ssh que nos sale en la web. <p>En ese momento hacemos el git remote add origin "pegamos la url".<p>lo subimos con git push -- set-upstream origin master y listo, una vez realizado esto ya lo tenemos subido a la nubie y ya solo con git push vamos guardando los cambios. </p>

 # Hacemos un commit y un push
 1. Realizamos una nuevo archivo que lo llamaremos fichero
 2. Para que se produzca el cambio escriimos git add . para empezar
 3. Hacemos git commit -m "añadimos el nuevo archivo al staging", vemos que se haya realizado correctamente a traves de git status.
 4. Por último, si vemos que todo esta bien lo publicamos con git push

 # Creamos una rama
 1. Creamos una rama con git branch developement, que es el nombre que le vamos a dar
 2. Para ver que esta correcto realizamos un git log --oneline --decorate --graph --all
 3. Vemos que sale el head con las ramas que hay y estas estan añadidas al staging
 4. Nos movemos al developement, y para ello, hacemos un git checkout developement.
 5. Cambiamos el texto de la pagina index.html que antes ponia hola git ahora pondrá Hola Mundo
 6. Añadimos el git add .  y el git commit -m con el comentario
 7. Para subir este cambio hay que hacer el git push --set-upstream origin developement, y ene ese momento podremos ir subiendo los cambios de la rama developement. 
 
 # Hacemos un Merge
 1. Seguimos en la rama developement y creamos un nuevo archivo que lo vamos a llamar developement.txt
 2. Escribimos en el el commit
 3. Lo subimos con git push
 4. Volvemos a master y en este añadimos el git merge developement -m "mezclamos developement"
 5. Vemos que se ha realizzado correctamente y lo subimos. 
