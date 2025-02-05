# Django REST Framework CRUD - Simple API

Este proyecto es una API CRUD desarrollada con Django Rest Framework (DRF). Permite gestionar proyectos mediante peticiones HTTP.

## 🚀 Acceso al Proyecto

La API está desplegada en Render y puedes acceder a ella en:

🔗 **Base URL:**  
[https://drf-simplecrud-0y23.onrender.com/api/projects/](https://drf-simplecrud-0y23.onrender.com/api/projects/)

## 📌 Endpoints y Métodos HTTP

| Método | URL                           | Descripción                                  |
|--------|-------------------------------|----------------------------------------------|
| GET    | `/api/projects/`              | Obtener la lista de proyectos                |
| GET    | `/api/projects/{id}/`         | Obtener detalles de un proyecto específico   |
| POST   | `/api/projects/`              | Crear un nuevo proyecto                      |
| PUT    | `/api/projects/{id}/`         | Actualizar un proyecto completo              |
| PATCH  | `/api/projects/{id}/`         | Actualizar parcialmente un proyecto          |
| DELETE | `/api/projects/{id}/`         | Eliminar un proyecto                         |

## 🛠 Uso con `curl`

### Obtener todos los proyectos

### En sh:

curl -X GET https://drf-simplecrud-0y23.onrender.com/api/projects/

## ⚡ Acceso a los Recursos (projects) con Thunder Client o Postman

Puedes manipular y acceder a los recursos de esta API utilizando herramientas como **Thunder Client** o **Postman**. Estas herramientas te permiten enviar solicitudes HTTP y probar los diferentes endpoints de forma sencilla.

### Ejemplo de Configuración:

- **URL Base:**  
  `https://drf-simplecrud-0y23.onrender.com/api/projects/`

- **Métodos Soportados:** GET, POST, PUT, PATCH, DELETE

- **Encabezados:**  
  `Content-Type: application/json`

- **Cuerpo de la Solicitud:**  
  Para crear o actualizar recursos, envía datos en formato JSON, por ejemplo:
  ```json
  {
    "name": "Nombre del Proyecto",
    "description": "Descripción del Proyecto"
  }
