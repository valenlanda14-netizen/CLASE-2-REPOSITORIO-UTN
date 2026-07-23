Para que sirve GIT?
para versionar nuestro proyecto/ guardar en versiones

Que es Github?
Aloja nuestro proyecto, hosting 

##como creo un repositorio con git?
Con el comando g it init, inicializamos nuestro repositorio local

Como podemos versionar nuestro codigo, es decir tener cambios y quiero guardar partida?
1 GIt add. Añade al area de preparacion los cambios realizados en el codigo, el . hace referencia a traer todos los arochivos en el directorio raiz(la carpeta del proyecto)
2 git commit -m"comentario"(es una foto o version/checkpoint de como esta el proyecto actualmente, toma en cuentea lo añadido por git add.)

como subimos nuestro commit al repositorio en la nube?(asumiendo que ya esta coenctado)
DEPENDE_
Si es lña primera vez que pusheas giut push -u origin main (para crear la main remota)
SI YA EXISTE la main remota, es simplemente git push

git branch -main

herramieenta SOURCE CONTROL INTERFAZ GRAFICA
agregamos(como git add) y comitteamos mas facil.