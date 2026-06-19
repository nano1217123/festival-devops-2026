# Festival DevOps Music Fest

## Descripción

Proyecto desarrollado para la práctica de Git, GitHub, Docker y Docker Compose del programa DevOps y Contenedores del SENA.

El proyecto simula la gestión de un festival de música utilizando una arquitectura básica compuesta por frontend y backend.

## Estructura del Proyecto

```text
festival-devops/
│
├── frontend/
│   ├── index.html
│   └── style.css
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── docker-compose.yml
└── README.md
```

## Tecnologías Utilizadas

* HTML5
* CSS3
* Python
* Flask
* Docker
* Docker Compose
* Git
* GitHub

## Control de Versiones

Para la gestión del proyecto se utilizó Git mediante:

* Commits
* Branches (ramas)
* Merge de funcionalidades
* Repositorio remoto en GitHub

Ramas implementadas:

* main
* feature-landing
* feature-backend

## Docker

Docker permite empaquetar la aplicación y sus dependencias en contenedores para facilitar su despliegue y ejecución.

## Docker Compose

Docker Compose permite administrar múltiples contenedores mediante un único archivo de configuración.

## Ejecución del Proyecto

Clonar el repositorio:

```bash
git clone URL_DEL_REPOSITORIO
```

Ingresar al proyecto:

```bash
cd festival-devops
```

Levantar los servicios:

```bash
docker compose up -d
```

Verificar contenedores:

```bash
docker ps
```

## Autor

Emiliano Flórez

Programa: DevOps y Contenedores (Docker)

SENA CTMA

[![Verificacion Proyecto](https://github.com/nano1217123/festival-devops-2026/actions/workflows/ci.yml/badge.svg)](https://github.com/nano1217123/festival-devops-2026/actions/workflows/ci.yml)