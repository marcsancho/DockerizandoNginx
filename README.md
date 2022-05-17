# DockerizandoNginx
Realizamos la instalación de docker, y instalamos un servidor nginx en el mismo


## Instalación de Docker
se puede ver como hemos instalado docker [En este link](https://github.com/marcsancho/InstalacionDocker)

## Instalación de la imagen Nginx
![image](https://user-images.githubusercontent.com/91566044/168890179-06640cf4-d346-4807-a5da-64ebba6f89ed.png)
<br>
Una vez instalado, podremos usar el comando `docker pull nginx` el cual nos descargara la imagen de nginx <br>
![image](https://user-images.githubusercontent.com/91566044/168890532-ec2b56f8-32f5-4ada-a43c-9dcbd870e1e2.png)
<br>
Con el siguiente comando iniciaremos la imagen de nginx<br>
![image](https://user-images.githubusercontent.com/91566044/168890636-85971485-fb14-4c51-8efa-f3e11bab259e.png)
<br>
Posteriormente se nos abrira la pagina inicial de nginx<br>

##Configuración de Nginx
Empezaremos creando una carpeta con el nombre Nginx en documentos, y en ella crearemos una subcarpeta llamada site-content para alojar nuestro html.<br>
Alli creamos el archivo html<br>
![image](https://user-images.githubusercontent.com/91566044/168892419-07dfb5f5-e726-4c01-9b74-3c18e9c6b788.png)<br>

Aqui tenemos el resultado

![image](https://user-images.githubusercontent.com/91566044/168892543-5b58a672-3d25-4146-93ae-a05dea8a2f93.png)<br>

##Crear imagen personalizada
Para ello usaremos `Dockerfile`, creando asi un archivo en la carpeta anterior y insertando en el el siguiente contenido:<br>
![image](https://user-images.githubusercontent.com/91566044/168892795-b96bc97b-2d60-493b-904a-1340f292c84d.png)<br>

El comando `FROM` extraera la ultima imagen de nginx, y asi se crear nuestra nueva imagen, la cual podremos correr donde queramos.
