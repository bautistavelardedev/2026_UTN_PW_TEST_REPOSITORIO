## Para inicializar un repositorio en GIT:

git init

// al inicializar el repositorio todos los archivos dentro de la carpeta se encuentran en estado "untracked"/sin seguimiento //

## Para hacer seguimiento de un archivo

git add nombre_archivo

## Para hacer seguimiento a todos los archivos de una carpeta

git add .

## O si quieren ignorar/o no dar seguimiento a archivos pueden crear en la raíz un archivo
.gitignore 

// Dentro del archivo .gitignore escribimos el nombre del archivo que queremos ignorar Ej: index.html
Y se le borrara la U de "untracked" al lado del nombre 

## Para versionar
    Para versionar el codigo debe estar añadido, el codigo que se versiona es el que esta añadido hasta el momento

## Para cambiar le nombre del branch principal (opcional)
git branch -M main

## Configuramos una direccion remota para nuestro repositorio
git remote add origin https://github.com/bautistavelardedev/2026_UTN_PW_TEST_REPOSITORIO.git

//Configura a donde se va a subir tu codigo

## Enviar el codigo a la direccion remota
git push -u origin main

## Como subir cambios a gihub?
git add . 
git commit -m 'nombre del cambio o version'
git push

## Para crear una rama usamos
git checkout -b nombre_rama 

## Para movernos entre ramas
git checkout  nombre_rama

# Para crear la ramificacion en github
git push -u origin nombre_rama

## Si ya existe la rama
git push 
