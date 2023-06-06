# MySQL V8 : Docker Container 

Este repositorio tiene un docker compose para construir la imagen y levantar un container de MySQL v8 en Docker.
Ideal para trabajar en local en aplicaciones que utilizan como base de datos MySQL.
Se requiere instalado

## Pre Requisites

* Docker Engine - Community
   Version: v24.0.2

* Docker Compose 
   Version: v2.18.1
---
## Project Setup

```
cd /opt/docker
```

```
sudo git clone https://github.com/francodev25/mysql_local_docker
```

```
cd mysql_local_docker
```


```
docker compose -f docker-compose.yml up -d
```

Deberías tener levantado el contenedor en el puerto indicado (ver docker-files/config/.env)
