# Demo de una Webapp con Python3, Web.py y SQLite3

## 1. Crear un Ambiente Virtual (Virtual Environment)

Crear un virtual environment para instalar las librerias necesarias de Python.

````shell
python3 -m venv .venv
````

## 2. Iniciar el Virtual Environment

Iniciar el virtual environment para instalar las librerías necesarias para el proyecto.

````shell
source .venv/bin/activate
````

## 3. Actualizar **PIP**

Actualizar el instalador de paquetes de Python **pip**.

````shell
pip install --upgrade pip
````

## 4. Instalar el micro-framework **web.py**

Instalar el *micro-framework* **web.py** para la creación de Aplicaciones Web utilizando Python.

````shell
pip install web.py
````

## 5. Crear el archivo **requirement.txt**

Crear el archivo **requirements.txt** con la lista de las librerías y versiones de cada una, necesarias para el proyecto.

````shell
pip freeze > requirements.txt
````

## 6. Crear el archivo **runtime.txt**

Crear el archivo **runtime.txt** con la version de Python3 utilizada.

````shell
python3 -V > runtime.txt
````

## 7. Crear el archivo **.gitignore**

Crear el archivo **.gitignore** para indicar las carpetas y archivos que no se van a sincronizar con el repositorio.

````shell
*.pyc
__pycache__/
.venv/
````

## 8. Indexar las carpetas y archivos

````shell
git add .
````

## 9. Crear el punto de control **commit**

Crear el punto control con los cambios realizados al proyecto.

````shell
git commit -m "CREATED configuración del virtual environment"
````

## 10. Sincronizar los cambios al repositorio

Sincronizar los cambios realizados al proyectos con el repositorio.

````shell
git push -u origin main
````