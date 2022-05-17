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
``<!DOCTYPE html>
<html lang="ES">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DockerizandoNginx</title>
</head>

<body>
    <h1>Marc Sancho Santandreu</h1>
</body>

</html``
