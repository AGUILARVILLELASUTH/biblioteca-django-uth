Descripción del proyecto

Este proyecto es una aplicación web desarrollada con Django que permite la gestión de una biblioteca. Incluye funcionalidades para administrar libros, usuarios y operaciones básicas del sistema.

El objetivo principal es aplicar conceptos de desarrollo web con Django, manejo de bases de datos y buenas prácticas de configuración para entornos de desarrollo y producción.

🚀 Tecnologías utilizadas
Python 3
Django
MySQL / MariaDB
HTML, CSS
Git y GitHub
PythonAnywhere (para despliegue)
⚙️ Instrucciones de instalación
1. Clonar el repositorio
git clone https://github.com/AGUILARVILLELASUTH/biblioteca-django-uth.git
cd biblioteca-django-uth
2. Crear entorno virtual
python -m venv venv
source venv/bin/activate  # En Linux/Mac
venv\Scripts\activate     # En Windows
3. Instalar dependencias
pip install -r requirements.txt
4. Configurar variables de entorno

Crear un archivo .env en la raíz del proyecto:

SECRET_KEY=tu_clave_secreta
DEBUG=True

DB_NAME=nombre_db
DB_USER=usuario
DB_PASSWORD=contraseña
DB_HOST=localhost
DB_PORT=3306
5. Aplicar migraciones
python manage.py migrate
6. Ejecutar el servidor
python manage.py runserver
Estructura del proyecto
biblioteca_django/
│
├── biblioteca_project/   # Configuración principal de Django
├── libros/               # Aplicación principal
├── templates/            # Plantillas HTML
├── static/               # Archivos estáticos (CSS, JS)
├── media/                # Archivos subidos
├── .env                  # Variables de entorno (no se sube)
├── manage.py
└── requirements.txt
