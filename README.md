# codigo-semana1
Semana 1 del Bootcamp Codigo

## Comandos para GIT

```
git init
```
- Este comando solo se hace una vez por proyecto, sirve para inicializar nuestro proyecto con git
- :eye: crear una :file_folder: carpeta oculta llamada ```.git```
```
git status
```
- Poder listar y ver si los archivos estan listo para subir
- ojo en caso los archivos no esten listos se veran de color rojo y cuando lo esten seran de color verde


```
git add .
git add nombre_de_archivo
```
- se encarga de agregar los archivos a la memoria de GIT, es decir los guarda en un stash

```
git commit -m "comentario"
```
- Crea un punto en la linea de tiempo de nuestros cambios y a estos se le es posible adjuntar un comentario
- :eye: Los comentarios deben estar relacionados a los cambios que hice, esto es una recomendacion

```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso github

```
git pull origin main
```
- Sirve para descargar los cambios de nuestro repositorio en la nube, en este caso github

#Ramas

```
git checkout -b nombre_del_branch
```
- Sirve para crear una nueva rama
```
git branch
```
- Sirve para listar las ramas

```
git push origin  develop
```
- Una vez creada la rama subimos la rama al github

```
git checkout nombre_del_branch
```
- Sirve para moverme entre ramas
- :eye: Si el checkout no tiene -b solo es para moverse entre ramas


```
git remote -v
```
- :eye: Sirve para ver la ubicacion de tu repositorio en la nube.... :eye:
