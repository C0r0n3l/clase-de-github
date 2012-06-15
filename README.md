clase-de-github
===============

Este es un ejercicio que parte del ejemplo tomada de la clase de cvander

una vez instalas GIT, debes configurarlo:

git config --global user.name "C0r0n3l"
git config --global user.email"cworldcwt@hotmail.com"

Generando tu Public Key:

ssh-keygen

leyendo tu llave para copiarla a Github:
cat ~/.ssh/id_rs.pub

Arrancando tu proyecto:

git init

touch README

git add README

git commit -m "tu primer commit"

git push origin master
