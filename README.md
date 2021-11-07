# workflow-practice
> Repositorio de prácticas para el flujo de trabajo en Github. Superplus3

## Comandos GIT importantes:

#### Para descargar un repositorio desde un servidor remoto. Ejemplo: Github.
```Shell
git clone git@github.com:pulidovpe/practica_workflow.git
```

#### El comando git status muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados.
```Shell
git status
```

#### El comando git add archivo.txt para agregar un nuevo archivo o uno modificado. Ejemplo:
```Shell
git add archivo.txt
```
#### El comando git add archivo.txt carpeta/otro_archivo.txt otra_carpeta/otro_archivo.txt Ejemplo:
```Shell
git add archivo.txt carpeta/otro_archivo.txt otra_carpeta/otro_archivo.txt
```
#### El comando git add -A  y git add --all para agregar todos los archivos del proyecto Ejemplo:
```Shell
git add -A
git add --all
```
#### El comando git log y git log --name-status permite ver informacion de los cambios hechosEjemplo:
```Shell
git log
git log --name-status
```
#### El comando git init se utiliza para iniciar git. Crea una zona llamada staging dentro de la memoria RAM donde
####se irán guardando los cambios que se hagan sobre el archivo. Ejemplo:
```Shell
git init
