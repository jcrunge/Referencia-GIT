# Referencia-GIT
Este es un pequeño manual de referencia básico que se vio en el curso de CIDWA.

**iniciar un proyecto**

	>git init
	
**ignora parte del proyecto (con expresiones regulares)**

	>git ignore
	
**verifica si una carpeta tiene git, si se puede hacer comit, cuantos tienen que ser agregados, etc**

	>git status

**crea una copia local del repositorio ejecutado**

	>git clone <url>.git

**crea un archivo cualquiera**

	>touch <nombre del archivo>
 
**agregar para no ignorar**

	>git add <nombre del archivo>
	
**Cuando se ha hecho un cambio, se guarda una nueva versión con commit**

	>git commit -m "MENSAJE"
		se guarda el archivo y esta listo para subirse

**reemplaza el master por la rama a la que quieres enviar tus cambios**

	>git push <rama>

**Configuración  de tu git**	

	>git config --global push.default [simple, matching]
	

**si se inicia con un init y deseas agregar desde github o algún otro**

	>git remote add origin https://github.com/<usuario>/<Tu_repositorio.git>
	

**Subirlo a github a tu rama maestra**

	>git push -u origin master

**cuando no se inicie el proyecto se tiene que hacer un repositorio vacío y clonarlo**

	>mkdir <repositorio>
	>git clone <url>.git

**crear una branch** 

	>git checkout -b <ramanueva>

**se cambia a una branch**

	>git checkout <nombre de la branch>

**vuelve a la rama principal**

	>git checkout master


**para actualizar tu repositorio local al commit mas nuevo**

	>git pull 

**fusiona otra rama a tu rama activa** 

	>git merge <branch>
