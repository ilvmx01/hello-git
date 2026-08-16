ssh
Flujo normal

- git init
- touch .gitignore (**/DS.Store)
- En Github creo repo vacio

Primero

creo archivos en mi carpeta
- git st

Deberías ver los archivos nuevos del proyecto como untracked files.
- git add .
- git status
- git commit -m "Agrego primer proyecto Java"

Verifica que tu rama se llame main:
- git branch (* main) (Si todavía dijera master, cámbiala: git branch -M main)

- git remote add origin git@github.com:*****/poo1.git

Comprueba que quedó conectado: 

- git remote -v

(origin...
(origin...

- git push -u origin main


RUTINA

- git st*
- git add .
- git commit -m "Descripción del cambio"
- git push

como ya use git push -u origin main
Git quedó enlazado con origin/main, así que en los siguientes cambios normalmente basta con:

- git push

Y para ver tu historial con el alias que creamos:
- git tree*


// Descargar a local 

- git fetch (historial de cambios)
- git pull (historial de cambios y los cambios)


//

- git clone (copia repositorios-mismo link)
- git fork (copia repositorios-info en otro repositorio) -> Sync + pull request (hacia el "original")
