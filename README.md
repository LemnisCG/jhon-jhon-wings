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

Supongamos que tenemos una rama que se llame dev-sebastian de la cual queremos traer sus cambios, Para ello nos vamos a cambiar a la rama de dev-sebastian con  
`git checkout dev-sebastian`

Vamos a traer sus cambios con  
`git pull`

Vamos a volver a nuestra rama con  
`git checkout dev-juan`

Para combinar los cambios vamos a utilizar   
`git merge dev-sebastian`

**Nota: Puede haber conflictos en esta operación los cuales deben ser resueltos antes de hacer commit de estos cambios**

finalmente para enviar los cambios al repositorio remoto  
`git add .`
`git commit -m "merge con dev-sebastian"`



