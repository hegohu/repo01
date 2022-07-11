># **Teoria sobre git**
## **Crear un repossitorio llamado repo**
 1. para crear un repositorio, primero debemos acceder a la consola de git.  
2. A continuacion, nos dirigimos al lugar donde queramos crear el repositorio, con los comandos siguientes:  

|Comando |Explicacion |  
|:---- |:----: |
|``pwd``|Escribiendo esta comanda, nos mostrarà laruta en la que nos encontramos|
|``cd carpeta``| Con este comando, substituyendo carpeta, por el nombre de la carpeta que corresponda, nos dirigiremos a la carpeta que queramos, siempre que este en el lugar que nos encontramos. |
|``cd ..``| Ejecutando esta comanda, nos enviara a un nivel superior.|  
|``mkdir repo``|Con este comando creamos una carpeta con el nombre repo|
***
Una vez creada la carpeta, ejecutaremos **``git init repo``**, para asi crear un archivo que permita controlar los canvios que se hagan en dicho repositorio.  

Despues de ejecutar el comando anterior, procedemos a entrar dentro de esa carpeta.  
Con el comando ``git status`` veremos que nos muestra como se encuentra en ese momento el repossitorio, ya sea que tenga archivos, o este vacio.  
***
Para añadir los archivos en el repositorio, aunque los creemos dentro de la carpeta, no estaran como "subidos", para ello ejecutaremos el comando ``git add`` seguido del nombre del archivo que queramos, por ejemplo, ``git add index.html``.  
En caso de que sean 2 o mas, podriamos escribir **``git add .``**  
De ese modo, subimos todos los archivos a la vez.
Para quitar el archivo *index.html* escribiriamos el comando ``git rm --cached index.html``.
---
***
Tras tener claro que no hemos de modificar, o subir/eliminar algun fitxero, procederemos a subir los fitxeros al repositorio local, ya que estavan en el stagging area.  
Ejecutamos el comando ``git commit -m`` seguido de algun comentario si queremos, como por ejemplo ``git commit -m añadido por pepito``.  
***
Con el comando **``git log``** podemos ver el historial de los comits que hemos realizado.  
Para enviarlo al repositorio web, escribimos ``git push``.  
  
