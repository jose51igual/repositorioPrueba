### Este archivo es de prueba
1. Aqui vamos a añadir informacion para usar los comandos.
2. Despues de hacer git init para inicializar el repositorio, modificamos el readme.
3. Seguidamente guardamos cambios y usamos git add . para añadir todos los archivos que hemos modificado al repositorio , que si quisieramos añadir algun archivo en especifico en vez de todos , deberiamos poner git add (nombre del archivo).
4. Despues de haber utilizado git add , utilizamos git commit -m "El mensaje del commit"
5. Ahora utilizamos git log para ver el registro de los commits que se han hecho, cuando lo han hecho, quien y el mensaje del commit.
6. Ahora como tenemos los datos guardados, si hacemos git checkout -- . o en vez del . el nombre del archivo , lo devolvera al estado del ultimo commit, ya hayas modificado el archivo o lo hayas borrado por equivocación o lo que sea.
7. Ahora vamos a hacer un commit con un mensaje escrito mal aposta para luego arreglarlo con git commit --amend
8. Para crear una nueva rama hacemos git checkout -b (branch) y el nombre de la rama a crear, en este caso usamos develop mismo.
9. 