>Permisos en Linux.
1. Los primeros 3 números están orientados al usuario, los siguientes 3 al grupo y los últimos 3 a otros.
2. Los siguientes dos nombres pertenecen al grupo y luego el usuario.

>Hard links and Soft Links.

Este tipo de conceptos se refieren a crear un acceso directo en el path inicial de Linux, suponiendo que todos los días debemos de ingresar al mismo path en Linux para realizar algún tipo de trabajo, podemos definir un link a ese path. 
	Un hard link se refiere a que si creamos un acceso directo a un archivo o ruta y eliminamos ese archivo o ruta, el link continua y se mantiene, caso contrario al soft link. 

El comando a utilizar es el siguiente: ln -s path/al/archivo_o_directorio
	Sabremos que se ha creado por que en el directorio raiz veremos la ruta con la letra "l" al inicio, puedes ejecutar un ls -la para verlo. 

