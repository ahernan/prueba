prueba de uso de GitHub
=======================

Instalacion
apt-get

Configuracion 

git config --global user.name ""
git config --global user.email ""

Genreacion de una Public Key

ssh-keygen

leo la llave para copiarla a GitHub web

cat ~/.ssh/id_rsa_git.pub
copio el texto y lo pego en la web de git

Dentro de la carpeta local arranco el proyecto

git init

touch README2

git add README2

git commit -m "el 1re commit"

git push origin master

