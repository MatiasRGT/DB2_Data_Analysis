# Trabajo de analisis de datos para DB2 - ULS
---
## Docker 🐳

Imagen base
``` bash
$ sudo docker pull jupyter/base-notebook
```

Run primera vez
```bash
$ sudo docker run -p 8888:8888 -v /home/matias/docker_volumes/db2_analisis_datos:/home/jovyan/work --name db2_jupyter jupyter/base-notebook
```
* Cambiar path al necesario
* Abrir enlace de localhost(127.0.0.1) desde consola la primera vez para abrir con token
---

De la segunda vez en adelante
``` bash
$ sudo docker start db2_jupyter
```

``` bash
$ sudo docker stop db2_jupyter
```

```bash
http://127.0.0.1:8888/
```
