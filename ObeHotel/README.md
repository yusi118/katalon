# ObeHotel
Pruebas Katalon de la pagina web https://www.demo-obehotel.com/


- https://docs.katalon.com/katalon-studio/docs/git-integration.html


----------------------------------------------------------Git: como se trabaja

Control de versiones. Se guarda en nube el proyecto, asi todo el mundo puede acceder.

Se hace un clon en local donde se trabaja y se crea una rama (version) para no dañar la master (rama principal desde donde partira todo el mundo, y la unica que quedara al finalizar el proyecto).

Se hacen los cambios deseados y se sube la rama a la nube, asi tenemos los cambios a salvo.

Se van haciendo commits ("pack" de archivos que ese han modificado, puedes añadir notas sobre los cambios), pull para actualizar la copia local con lo que tienes en la nube (asi se evitan errores).

Push para subir los cambios.

Cuando ya se haya acabado el proposito de la rama se une (Merge)  con la master, haciendo pull, merge y push.

NOTA: Si hay conflictos (dos personas han modificado el mismo archivo) cuidado, ya que puedes sobreescribir y borrar el trabajo del compañero. En este caso se tendran que ver las dos versiones y hacer una unica con los cambios de los dos manualmente.

---------------------------------------------------------------Activar Git Katalon

1. Window - Preferences - Katalon - Git - Marcar checkbox

------------------------------------------------------------Clonar Repositorio

1. Arriba a la izquierda hay un rombo rojo, es donde podremos realizar acciones con git

2. Pagina github --> en el proyecto hay un boton verde que pone Clone, darle y copiar el enlace que aparece

3. Katalon --> Click al desplegable de Git - Clone project - pegar enlace y rellenar con vuestra cuenta github - Next... - Cuando salga Directory guardar donde querais, si no se toca se crea una carpeta Git en la carpeta del usuario

4. Se descargara el proyecto

--------------------------------------------------------------Crear una rama

Tip: Es importante crear una Rama de trabajo para cada uno y cuando hayas finalizado unirlo con la master

1. Katalon --> Click al desplegable de Git - Manage Branches - New Branch

2. Nombrar la rama, nombre relacionado con lo que se trabajara en ella 

3. Select... - selecionar la rama de la cual queremos partir, suele ser la master 

4. Finish

------------------------------------------------------------------Subir cambios 

1. Katalon --> Click al desplegable de Git - Commit

2. Se abre a bajo una pestaña, nos apareceran los archivos que se han modificado

3. Commit Message: escribir un comentario sobre los cambios que se han hecho (`mejor organizado y mas facil de encontrar versiones)

4. Escribir el correo de github del autor y de quien hace el commit (si no sale ya automaticamente) ---> FORMATO: nombre <correo@electronico.com>

5. Commit (SIN push, tendremos que actualizar primero)

6. SI ES LA PRIEMRA VEZ, SALTAR ESTE PASO:  Click al desplegable de Git - Pull

7. Click al desplegable de Git - Push

8. Por defecto aparece el nombre de la rama local en uso (si es donde estan los cambios, ya esta)

9. Introducir el usuario y contraseña de github (si los pide)

10. Finish

------------------------------------------------------Cambiar de rama 

1. Katalon --> Click al desplegable de Git - Manage Branches - Checkout Branch

2. Seleccionas la rama
