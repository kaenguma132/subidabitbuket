# Ejecicios basicos con Bitbuket Alejandro Torres

## Pasos ha realizar en git lab
- Primero pasamos a realizar la creacion del repositorio desde la pagina web una vez hemos entrado pulsando en create repositorio ![GitHub Logo](/gitbuk/1.png)
- Tenemos rellenar los apartados de proyecto y repositorio y dejar por defecto el private y pulsamos en create repository ![GitHub Logo](/gitbuk/2.png)
- comprobamos que se ha creado correctamente ![GitHub Logo](/gitbuk/3.png)
- una vez echo esto tenemos que generar una contraseña como se hizo en el github, para hacer esto tenemos que ir a los ajustes/contraseña de la aplicacion y crear una nueva![GitHub Logo](/gitbuk/3.5.png)
- Le damos todos los permisos aunque se le podrian restingir algunos ya que esto es una prueba para subir archivos ![GitHub Logo](/gitbuk/4.png)
- Esperamos un momento y vemos como nos ha generado la clave " para este caso la he dejado medio visible"
![GitHub Logo](/gitbuk/5.5.png)

## Pasos a realizar en la máquina local antes de subir los archivos a git lab

- En el el escritorio lo que podemos hacer es clonar el repositorio con el comando **git clone https://kaenguma132@bitbucket.org/kaenguma132/subidagitbuk.git** devido ha que he tenido problemas a la hora de hacer el push lo he echo asi  ![GitHub Logo](/gitbuk/5.75.png)
- Ahora desde el propio terminar entramos a la carpeta con el comando **cd** y el nombre de la carpeta a la cual queremos entrar "si la capeta no está en la ubicacion donde nosotros estamos en la consola tendremos que escribir la ruta entera para poder situarnos dentro de ella" insertar imagen ![GitHub Logo](/gitbuk/7.png)
- Una vez dentro crearemos con el comando sudo **touch / nano /vi** algun docuemto para asi poder hacer la prueba de la subida de archivos y usamos el comando **ls** para verificar que se han creado correctamente insertar imagen  ![GitHub Logo](/gitbuk/8.png)

## Pasos a realizar para la subida a gitlab

- Primero tenemos que añadir el proyecto al control de versiones de git con el comando **sudo git init** para esto tenemos que estar dentro de la carpeta que queremos añadir, que en este caso es subidagitlab ![GitHub Logo](/gitbuk/9.png)
- Una vez añadido el proyecto al control de versiones hacemos el comando**git status** y vemos que el archivo que hemos creado antes no esta añadido al proyecto ![GitHub Logo](/gitbuk/10.png)
- Para añadir el archivo al proyecto tenemos que usar el comando **git add "nombre del archivo"**![GitHub Logo](/gitbuk/11.png)
- Volvemos a hacer un **git status** y vemos que se ha sincronizado correctamente![GitHub Logo](/gitbuk/12.png)
- Ahora pasamos a registrar cambios en el historial con el comando **git commit -m "Comentario asociado"** y vemos que se ha realizado correctamente![GitHub Logo](/gitbuk/13.png)
- Una vez hemos hecho el comit no hace falta usar el comando**git remote origin https://gitlab.com/atorresrod1/ejerciciosbasico.git** ya que una vez que se ha clonado esta apuntando directamente al repositorio 
- Ahora toca subir el archivo al repositorio ha traves del comando **git push origin master** ![GitHub Logo](/gitbuk/14.png)

## Comprobarque se ha subido el archivo a gitlab


- Actualizamos la pagina podemos ver que se ha subido correctamente ![GitHub Logo](/gitlab/15.png)
