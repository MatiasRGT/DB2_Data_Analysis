# Trabajo de analisis de datos para DB2 - ULS
---
### Docker 

``` bash
$ sudo docker pull jupyter/base-notebook
```

```bash
$ sudo docker run -p 8888:8888 -v /home/matias/docker_volumes/db2_analisis_datos:/home/jovyan/work --name db2_jupyter jupyter/base-notebook
```
Abrir enlace de consola la primera vez para el token

``` bash
docker start db2_jupyter
```

``` bash
docker stop db2_jupyter
```

```bash
http://127.0.0.1:8888/
```
