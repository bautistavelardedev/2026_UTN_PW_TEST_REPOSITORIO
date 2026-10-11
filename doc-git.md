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