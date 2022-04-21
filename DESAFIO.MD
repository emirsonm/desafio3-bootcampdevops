# SOLUCION AL DESAFIO MYSQL + NODEJS + NGINX

## ARQUITECTURA

| Contenedor | Servicio | Puerto |
|:----------:|:--------:|:------:|
|     db     |   Mysql  |  3306  |
|     app    |  Nodejs  |  3000  |
|    nginx   |   nginx  |  8080  |

## AJUSTES


1 Se agrega la deficion para la red node-network al archivo docker-compose.yaml

2 Se modifica el nombre de la base de datos en la configuracion nodejs

3 Se modifica el Dockerfile de nodejs

4 Se agrega el copy del archivo nginx.conf al Dockerfile de nginx

5 Se agrega el puerto 3000 al archivo nginx.conf

![Resultado en el navegador](image/desafio3.png)
