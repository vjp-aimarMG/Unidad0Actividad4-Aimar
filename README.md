# Unidad0Actividad4-Aimar
1. Creamos un nuevo directorio con:
**echo "# PPS-Unidad0Actividad4-Aimar" >> README.md**
**git init**
**git add README.md**
**git commit -m "first commit"**
**git branch -M main**
**git remote add origin git@github.com:git@github.com:vjp-            aimarMG/Unidad0Actividad4-Aimar.git**
**git push -u origin main**
2. Creamos dos archivos .txt y un directorio llamado Excluded, después el archivo .gitignore donde vamos a añadir dentro todas las extensiones .txt y el directorio Excluded recientemente creado, después de eso comprobaremos el estado para ver si realmente no rastrea los archivos. 
![](/imagenes/1.png)
3. Lo siguiente sería crear un archivo html con un texto dentro.
![](/imagenes/2.png)
4. Después de guardarlo haremos un **git add, git commit, git push**
5. Si nos dirigimos a git podremos ver que efectivamente se han subido los cambios.
![](/imagenes/3.png) 
6. Para comprobar el funcionamiento abriremos otro terminal y ejecutaremos este comando php -S 0:8080, después en un buscador buscamos el puerto y visualizamos el html que hemos creado.
![](/imagenes/4.png) 
7. El siguiente paso será crear una copia del archivo html y modificar el original, después con **git diff** nos mostrará la diferencia de los archivos que no han sido añadidos.
![](/imagenes/5.png) 
8. Si refrescamos el navegador podremos ver el cambio realizado.
![](/imagenes/6.png) 
9. Por otro lado modificaremos el html desde github y con un **pull** nos lo bajaremos al repositorio local y visualizaremos el cambio.
![](/imagenes/7.png) 
10. Vamos a mostrar ahora los log, para ello utilizaremos el comando **git log**.
![](/imagenes/8.png) 
11. Ahora para mostrar los últimos 3 commit utilizaremos el comando **git log  -3**.
![](/imagenes/9.png) 
12. Podemos utilizar el comando **pretty** seguido de un modificador para diferentes modelos de datos, en mi caso utilizaré **online**.
![](/imagenes/10.png) 
13. Si queremos mostrar varios log pero con la diferencia entre ellos utilizaremos **-p**.
![](/imagenes/11.png) 
14. Para mostrar el log de cierto tiempo determinado se utiliza el modificador **--since**.
![](/imagenes/12.png) 
15. A continuación vamos a listar las ramas existentes .
![](/imagenes/13.png) 
16. Ahora vamos a crear una nueva rama, para ello usaremos **git branch Vers1**.
![](/imagenes/14.png) 
17. Modificamos el archivo **index**.
![](/imagenes/15.png) 
18. Ahora haremos un push pero a la rama nueva creada.
![](/imagenes/16.png) 
* Podemos ver que en la rama **main** no se han aplicado los cambios.
![](/imagenes/17.png) 
* Pero en la rama **Vers1** si.
![](/imagenes/18.png) 