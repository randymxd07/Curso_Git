# Para configurar el usuario que va a trabajar con git
git config --global user.name "randymxd06"

# Para verificar el usuario que está trabajando con git
git config user.name

# Para configurar el correo electrónico a usar con git
git config --global user.email "randym0624@gmail.com"

# Para verificar el correo que está trabajando con git
git config user.email

# Para iniciar el proyecto
git init

# Para ver el estado en que se encuentran los archivos
git status

# Para añadir un archivo ponemos git add seguido del nombre del archivo
git add index.html

# Para añadir todos los archivos ponemos git add seguido de un punto
git add .

# Para hacer commmit con un mensaje
git commit -m "Este es el primer commit del proyecto"

# Para borrar el commit que se acaba de hacer con git rm --cached y el nombre del archivo que quieres quitar del commit
git rm --cached index.html

# Para ver el historial de commits
git log

# Para ver el estado, la cantidad de archivos nuevos, las lineas que agregaste a los commits que hiciste, etc
git log --stat

# Para mostrar los commits en una sola linea
git log --oneline

# Para regresar al commit que se hizo tiempo atras
git checkout numerodelcommitaregresar

# Para ver las ramas que tenemos en el proyecto
git branch

# Para cambiar de rama
git checkout nombredelarama

# Para crear una rama
git checkout -b nombredelarama