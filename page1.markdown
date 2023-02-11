---
layout: page
title: Page1
permalink: /page1/
---

# Minikube

En este document hablaremos the Minikube.

## Listar Minikube 

Ejecutemos el comando para listar la version the minikube instalada localmente.

```bash
-> minikube version
minikube version: v1.28.0
commit: 986b1ebd987211ed16f8cc10aed7d2c42fc8392f
```

## Verificar Instancias de Kubernetes

Verificar las instancias the kubernetes installadas corrientemente.

```bash
-> minikube profile list
🎉  minikube 1.29.0 is available! Download it: https://github.com/kubernetes/minikube/releases/tag/v1.29.0
💡  To disable this notice, run: 'minikube config set WantUpdateNotification false'

|-------------------|-----------|---------|--------------|------|---------|---------|-------|--------|
|      Profile      | VM Driver | Runtime |      IP      | Port | Version | Status  | Nodes | Active |
|-------------------|-----------|---------|--------------|------|---------|---------|-------|--------|
| minikube-v1.23.4a | hyperkit  | docker  | 172.16.156.9 | 8443 | v1.23.4 | Stopped |     3 |        |
|-------------------|-----------|---------|--------------|------|---------|---------|-------|--------|
```

> NOTA: la lista es dinamica y puede cambiar