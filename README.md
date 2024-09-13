# blackJackPython

# Guía para instalar y configurar FastAPI en Python


## 1 bajar el código
git clone https://github.com/marcosmdc/blackJackPython.git
## 2. Instalar Python

Para comenzar, es necesario instalar Python en tu máquina:

- Ve a la página oficial de Python: [https://www.python.org/downloads/](https://www.python.org/downloads/)
- Descarga la última versión compatible con tu sistema operativo.
- Durante la instalación, **marca la opción "Add Python to PATH"** para asegurarte de que Python esté accesible desde la terminal.

## 3. Crear y activar un entorno virtual

Es recomendable trabajar en un entorno virtual para aislar las dependencias del proyecto. Para crearlo y activarlo, sigue estos pasos:

### Crear el entorno virtual

En la terminal, dentro de la carpeta de tu proyecto, ejecuta:
python -m venv venv
source venv/Scripts/actívate

## 4 instalar librerías:
pip install uvicorn
pip install fastapi


## 5 ejecutar app
	uvicorn main:app

## 6 forwardear en visual studio code
 	hacer publica la app 

