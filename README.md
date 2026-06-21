[![Verificacion Proyecto](https://github.com/nano1217123/festival-devops-2026/actions/workflows/ci.yml/badge.svg)](https://github.com/nano1217123/festival-devops-2026/actions/workflows/ci.yml)

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

## Integración Continua (GitHub Actions)

El proyecto implementa un flujo de Integración Continua (CI) mediante GitHub Actions.

### Workflow de Validación

Archivo:

```text
.github/workflows/ci.yml
```

El workflow se ejecuta automáticamente cuando se realiza un push a la rama `main`.

### Validaciones implementadas

* Verificación de existencia de `frontend/index.html`
* Verificación de existencia de `frontend/style.css`
* Verificación de existencia de `backend/app.py`
* Verificación de existencia de `README.md`

Si alguno de estos archivos no existe, la ejecución falla automáticamente.

### Beneficios

* Detección temprana de errores.
* Validación automática de la estructura del proyecto.
* Mayor calidad del código antes de integrar cambios.
* Automatización de tareas repetitivas.

El estado de la ejecución puede consultarse mediante el badge ubicado en la parte superior de este documento.

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
