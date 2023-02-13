---
layout: page
title: Docker
permalink: /docker/
nav_order: 2
has_children: true
has_toc: false
---

Parent page for Docker

# Docker

En este document hablaremos the Docker.
_El objectivo es enternder la manera de usar esta herramienta para crear un ambiente para probar varios aspectos de Docker._

## Listar la version de Docker 

Ejecutemos el comando para listar la version the minikube instalada localmente.

```bash
-> docker version
Client:
 Cloud integration: v1.0.29
 Version:           20.10.22
 API version:       1.41
 Go version:        go1.18.9
 Git commit:        3a2c30b
 Built:             Thu Dec 15 22:28:41 2022
 OS/Arch:           darwin/amd64
 Context:           default
 Experimental:      true
```

Tambien se pueded listar de esta manera.
```
-> docker --version
Docker version 20.10.22, build 3a2c30b
```

---

El comando `docker image ls` lista las imagenes de docker presentes en el sistema.

> NOTA: la lista es dinámica y puede cambiar