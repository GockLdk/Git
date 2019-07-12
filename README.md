# Comandos Basicos del uso de Git y Github desde Terminal

### Instalacion
***sudo install git***

### Configuracion
- Nombre

***sudo git config --global user.name "nombre"***
- Mail

***sudo git config --global user.email "mail"***
- Enlista con que nombre y mail con los que se hara el commit
***sudo git config --global --list*** 

**Nota:** Entre las comillas se pone el nombre o mail deseado.

### Commit
- Inicilaizar repositorio en la carpeta donde se ubica en la terminal.
***git init***
- Ver el estado de los archivos dentro de la carpeta.
***git status***
- Agregar archivos.
***git add OPCION***
	- **Nombre del archivo**.
	- ** . ** o **-A** para agregar todo lo que se encuentre en la carpeta.
- Crear el Commit
***git commit -m "comentario del commit"***
- Historial de commit
***git log***

### Subiendo al Repositorio
#### Antes debiste crear un repositorio en Github.
- Una vez creado sincronizas la carpeta con el repositorio.
***git remote add origin LINK***
Donde LINK es el link del repositorio.
- Y finalmente subimos el commit al repositorio.
***git push -u origin master***

### Extras
- Borrar archivo de un commit ya existente.
***git rm NombreArchivo***
- Borrar carpeta de un commit ya existente.
***git rm -r NombreCarpeta***
- Clonar un repositorio donde seas contribuidor.
***git clone LINK***
Donde LINK es el link del repositorio.
