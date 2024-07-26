# Reto Django REST Framework 

Este es un proyecto Django REST Framework para gestionar vulnerabilidades. Este README explica cómo configurar, ejecutar y probar la aplicación. 

El objetivo de la aplicación es gestionar la seguridad de los sistemas desplegados en la infraestructura Cloud mediante la integración con la base de datos de vulnerabilidades del NIST (https://nvd.nist.gov/developers/vulnerabilities). 

La aplicación ofrece una API REST que incluye los siguientes métodos:
1. **GET**: Listado total de las vulnerabilidades.
2. **POST**: Registrar vulnerabilidades como fixeadas.
3. **GET**: Listado de vulnerabilidades excluyendo las fixeadas.
4. **GET**: Información resumida de vulnerabilidades por severidad.
5. **GET**: Listado de vulnerabilidades fixeadas.
6. **GET**: Busqueda de vulnerabilidad por id

## Requisitos

- Python 3.8 o superior
- Django 3.0 o superior
- Django REST Framework
- Otras dependencias listadas en `requirements.txt`

## Instalación


