  Exposición: Usando Python Flask a partir de un proyecto en github, observando
              la secuencia de commits como metodología para progresar en la
              construcción de una nueva aplicación.

Paso 1: Descargamos virtual environment de python si no lo tenemos: 
	$ sudo apt-get install python3-venv

Paso 2: Creamos un entorno virtual para trabajar con pip: 
	$ python3 -m virtualenv env

Paso 3: Activamos el entorno virtual para trabajar en el: 
	$ source env/bin/activate  -- para salir del entorno virtual ejecutamos 
	$ deactivate

Paso 4: Instalamos todo lo que vamos a necesitar: 
	$ pip install flask
	$ pip install feedparser
	
Paso 5: Ejecutamos el proyecto:
	$ python headlines.py 

Paso 6: Lo visitamos en localhost:5300.


