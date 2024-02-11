# Sitio web de jhon jhon wings
## Resumen de comandos git utilizados 
### Creacion de una Rama

Inicializando un repositorio
`git init` 

Creando la Rama main
`git branch -M main`

Agregando los cambios al stagimg area
`git add .`

Enviando un commit
`git commit -m "Mensaje"`

Para enviar los cambios al repositorio remoto 
`git push`

Creando una rama dev-juan a partir de main
`git checkout -b dev-juan`

Haciendo disponible la rama en el repositorio remoto
`git push origin dev-juan`

### Trabajo colaborativo 
Para poder hacer git push al repositorio remoto vamos a utilizar 
`git push --set-upstream origin dev-juan`

**Nota: Esto se debe repetir en las otras ramas**

Supongamos que tenemos una rama que se llame dev-sebastian de la cual queremos traer sus cambios
``



