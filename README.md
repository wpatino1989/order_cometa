# Proyecto Principal

Este repositorio contiene dos submódulos: `backend` y `frontend`. Ambos submódulos están organizados como proyectos independientes con su propia configuración y scripts.

## Estructura del Proyecto

- **backend/**: Submódulo para la aplicación backend.
- **frontend/**: Submódulo para la aplicación frontend.

### Backend

- **Descripción**: El submódulo `backend` contiene el código fuente para la parte del servidor de la aplicación. Este proyecto está basado en Django y maneja las operaciones del lado del servidor, como la gestión de datos y las API.
- **URL del Repositorio**: [https://github.com/wpatino1989/beer_order.git](https://github.com/wpatino1989/beer_order.git)

### Frontend

- **Descripción**: El submódulo `frontend` contiene el código fuente para la parte del cliente de la aplicación. Este proyecto está basado en Next.js y maneja la interfaz de usuario y la interacción del cliente.
- **URL del Repositorio**: [https://github.com/wpatino1989/beer_order_frontend.git](https://github.com/wpatino1989/beer_order_frontend.git)

## Instrucciones de Configuración

Para configurar y ejecutar los submódulos, sigue estos pasos:

### Clonar el Repositorio Principal

Primero, clona el repositorio principal:

```bash
git clone https://github.com/tu_usuario/tu_repositorio_principal.git
cd tu_repositorio_principal
```

## Requisitos

- Docker
- Docker Compose

## Instalación

1. Construye la imagen Docker:

    ```sh
    docker-compose build
    ```

2. Ejecuta la aplicación:

    ```sh
    docker-compose up
    ```
