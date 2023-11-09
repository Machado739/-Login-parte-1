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
## Cómo Ejecutar la Aplicación

1. **Descarga el Código Fuente:**

   Clona este repositorio en tu máquina local. Abre la terminal y ejecuta el siguiente comando:

   ```bash
   git clone https://github.com/tu-usuario/practica-login-flask.git
Entra al Directorio del Proyecto:

Cambia al directorio del proyecto con el siguiente comando:

bash
Copy code
cd practica-login-flask
Crea y Activa un Entorno Virtual:

Crea un entorno virtual para el proyecto. En la terminal, ejecuta:

bash
Copy code
python -m venv env
Luego, activa el entorno virtual:

En sistemas basados en Unix:

bash
Copy code
source env/bin/activate
En sistemas Windows:

bash
Copy code
.\env\Scripts\activate
Instala las Dependencias:

Instala las dependencias del proyecto usando el siguiente comando:

bash
Copy code
pip install -r requirements.txt
Ejecuta la Aplicación:

Inicia la aplicación con el siguiente comando:

bash
Copy code
python src/app.py
Abre tu Navegador:

Abre tu navegador web y visita http://127.0.0.1:5000/ para ver la aplicación en funcionamiento.

Ahora deberías ver la página de inicio de sesión. Puedes probar el inicio de sesión con los usuarios de prueba o personalizar la aplicación según tus necesidades.

## Dificultades
Durante el desarrollo de esta práctica, podrías enfrentar algunas dificultades comunes:

Manejo de Formularios en Flask-WTF: Asegúrate de comprender cómo funcionan los formularios en Flask-WTF y cómo vincularlos con las rutas de Flask.

Implementación de Funcionalidades de Login: Implementar la lógica de autenticación y manejo de sesiones puede ser desafiante. Consulta la documentación de Flask-Login para obtener orientación.

Diseño y Estilos: Integrar estilos personalizados y utilizar Bootstrap puede requerir ajustes y experimentación para lograr el aspecto deseado.

Estructura del Proyecto: Organizar tu proyecto de manera efectiva puede ser crucial. Asegúrate de entender la estructura de directorios y cómo Flask maneja las plantillas.
