# CRUD Application

Este proyecto es una aplicación básica CRUD (Crear, Actualizar, Eliminar) implementada en Python. El proyecto está estructurado en varios componentes que se encargan de manejar diferentes aspectos de la aplicación.

## Estructura del Proyecto

El proyecto está dividido en las siguientes carpetas y archivos:

- **controller**: Contiene la lógica para manejar las solicitudes y coordinar las operaciones de CRUD con los datos.
- **index.py**: Archivo principal donde se ejecuta la aplicación. Este archivo coordina la inicialización de la aplicación.
- **models**: Aquí se definen los modelos de datos, los cuales representan las entidades que la aplicación maneja, como registros en una base de datos.
- **view**: Contiene las vistas o plantillas de la aplicación, que definen cómo se presentan los datos al usuario.

## Instalación

1. Clona o descarga el repositorio.
2. Navega a la carpeta del proyecto y asegúrate de tener Python instalado.
3. Instala las dependencias necesarias (si las hay) utilizando `pip`:
    ```bash
    pip install -r requirements.txt
    ```
4. Ejecuta la aplicación con el siguiente comando:
    ```bash
    python index.py
    ```

## Funcionalidades

La aplicación soporta las siguientes operaciones CRUD:

- **Crear**: Permite agregar nuevos registros a la base de datos.
- **Leer**: Permite visualizar los registros existentes.
- **Actualizar**: Permite modificar los registros existentes.
- **Eliminar**: Permite eliminar registros de la base de datos.

## Uso

1. Inicia la aplicación.
2. Accede a las vistas definidas en el archivo **view** para interactuar con la base de datos a través de la interfaz de usuario.
3. Realiza las operaciones CRUD según sea necesario, utilizando las rutas y formularios proporcionados.


