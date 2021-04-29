# Comandos de clase

    git clone URL

> Clonamos repositorio remoto


    git add archivo

> agregamos al Staging Area


    git commit -m 'titulo' -m 'descripción'

> Agregamos a base de datos con un mensaje descriptivo


## Solucionando errores locales

> cuando cometemos un error de tipeo en el commit, podemos solucionarlo "SI ES EL ULTIMO COMMIT" con el comando 

    git commit --amend


> primer caso, cuando guardamos archivo y cerramos editor sin agrgar ni a Sting Area ni a Repositorio
    git diff
    git checkout -- archivo

> segundo caso cuando guardamos archivo, cerramos editor y SI agregamos a Staging Area

   git diff
   git restore --staged archivo
   git checkout -- archivo

> tercer caso cuando guardamos, cerramos editor, agregarmos al Staging Area y Comiteamos!!!

    git reset --hard b8ca7bb29ac03f

