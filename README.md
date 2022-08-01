# Pasos 

* Bajar Jar

* Generar Docker File

* Compilamos la imagen 
```
$  docker build -f .\Dockerfile --no-cache  -t hduchen/ejercicio6:2.0.0 . 
```
* validamos la imagen 
```
$ docker image ls
```
* Exponemos el puerto y visualizmos en localhost
```
$ docker run --name -ejercicio06  -p 3011:8080 hduchen/ejercicio6:2.0.0  
```
* Subimos la imagen a dockerhub
```
$ docker push hduchen/ejercicio6:2.0.0     
```
* link dockerhub

https://hub.docker.com/repository/docker/hduchen/ejersicio2