# Estoy realizando una práctica donde bajé la información del repositorio https://github.com/jcdiazvale/vanilla  a mi computador local, para luego incluir un subdiretorio en C:\code\vanilla\ llamado juan_c_segunda_prueba, dentro de este último cree un archivo “juan_c.dm”. Y por último será subido a repositorio en la github.

1.	Te vas al terminal con “cmd” para los que tienen windows
2.	cd\ para moverte a la raíz del disco Local C:\
3.	md code para crear la carpeta “code”
4.	cd code para posicionarte dentro de la carpeta “code”, y luego 
5.	git clone https://github.com/jcdiazvale/vanilla para importar los datos desde el repositorio creado en la web hithub.
6.	md juan_c_segunda_prueba para crar una carpeta nueva llamada “juan_c_segunda_prueba”
7.	cd juan_c_segunda_prueba para posicionarme dentro la carpeta “juan_c_segunda_prueba”
8.	dir >juan_c.dm para crear el archivo “juan_c.dm”
9.	Con Notepad editas el archivo juan_c.md e insertas lo que quieras agregar y lo guardas.
10.	cd.. para salir del directorio actual y bajar a C:\code\vanilla\
11.	git status para ver si vas bien para lo cual deben salir unas letras están en rojo.
12.	git add un espacio y luego un punto “.” para incluirlo.
13.	git status para ver si vas bien para lo cual deben salir unas letras están en verde que significa que lo incluiste satisfactoriamente.
14.	git commit -m "Creada mi segunda carpeta con instructivo" 
15.	git pull origin master para bajar la información de los demás integrantes
16.	git push origin master para sincronizar con el repositorio
17.	validar en el repositorio de github la obra de arte.
