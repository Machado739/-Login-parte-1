# Login-parte-1
# Práctica 5: Login con Flask

Este es un proyecto de práctica que implementa un sistema básico de inicio de sesión utilizando Flask, Flask-Login, y Flask-WTF. La aplicación consta de dos páginas principales: la página de inicio de sesión y la página de inicio.

## Estructura del Proyecto

El proyecto sigue la siguiente estructura de directorios:

- `database`: Carpeta para almacenar archivos de base de datos (aún no implementados en esta práctica).
- `src`: Carpeta principal que contiene el código fuente de la aplicación.
  - `models`: Carpeta para modelos de datos (aún no implementados en esta práctica).
  - `static`: Carpeta para archivos estáticos como CSS e imágenes.
    - `css`: Carpeta que contiene archivos CSS personalizados.
    - `img`: Carpeta para imágenes.
  - `templates`: Carpeta que contiene las plantillas HTML.
    - `auth`: Carpeta con la plantilla de la página de inicio de sesión.
- `env`: Carpeta del entorno virtual para las dependencias del proyecto.

## Configuración y Ejecución

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tu-usuario/practica-login-flask.git
Crea y activa un entorno virtual:

bash
Copy code
cd practica-login-flask
python -m venv env
source env/bin/activate  # Para sistemas basados en Unix
Instala las dependencias:

bash
Copy code
pip install -r requirements.txt
Ejecuta la aplicación:

bash
Copy code
python src/app.py
Abre tu navegador y visita http://127.0.0.1:5000/ para ver la aplicación en acción.
