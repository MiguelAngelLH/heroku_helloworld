# heroku_helloworld
Heroku Hello World FastAPI

## Lista de archivos necesarios

Archivos de configuración necesarios para ejecutar la API:
|No.|Archivo|Descripción|
|--|--|--|
|1.|.gitignore|Archivos y directorios que no se suben al repositorio|
|2.|requirements.txt|Librerías necesarias para ejecutar la API|
|3.|runtime.txt|Versión de Python que se usará en Heroku|
|4.|Profile|Configuración de Heroku para ejecutar la API|
|5.|main.py|Hola Mundo en FastAPI|
|6.|README.md|Archivo con la información general del proyecto|


## Run API

bash
gunicorn -k uvicorn.workers.UvicornWorker --bind 0.0.0.0:8000 main:app
