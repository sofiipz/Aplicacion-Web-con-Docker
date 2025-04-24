# Despliegue de Aplicación Multi-Contenedor con Docker

_Práctica de la asignatura de Sistemas Informáticos - 1º DAM_  

Este proyecto consiste en el despliegue de una aplicación web formada por tres contenedores usando Docker. Se trata de una práctica educativa para aprender los conceptos básicos de virtualización y redes con contenedores, dentro de la asignatura de Sistemas Informáticos.

## ¿En qué consiste la práctica?

La práctica tiene como objetivo montar un entorno con tres servicios:

- **MySQL**: base de datos que simula el almacenamiento de información.
- **Node.js**: backend que devuelve un mensaje como respuesta a las peticiones web.
- **Nginx**: servidor que actúa como intermediario, redirigiendo las peticiones del navegador al backend.

Todos los servicios están conectados en una red interna de Docker, lo que permite que se comuniquen entre sí mediante sus nombres de contenedor.

Se ha utilizado `Docker Compose` para facilitar la configuración y despliegue del entorno completo.

## Acceso a la aplicación

Una vez los contenedores están en ejecución, se puede acceder a la aplicación desde el navegador en: http://localhost:8080

---

## Fecha: Abril de 2025
