# dapw-python
### Despregamento aplicación python en entornos de desa e prod
En este tarea, que consta de 3 partes:
<<1>> Entorno de desarrollo -> En esta parte implementamos un servidor uwsgi con django y lo ejecutamos en un entorno virtual de desarrollo creado previamente.
<<2>> Utilización de un IDE de desarrollo en el host -> En esta parte instalamos en el IDE Visual Studio Code la extensión SFTP en el que vamos a configurar la conexión remota a nuestro servidor de desarrollo y así poder realizar los cambios pertinentes en nuestro host local. También vamos a configurar un repositorio git donde gestionar los cambios que realizamos en local.
<<3>> Entorno de producción -> Aquí es donde vamos a generar un entorno virtual de python pero ya destinado a producción utilizando uwsgi y un servidor web (en este caso se va a utilizar apache2), además de una base de datos como mysql o mariadb.
