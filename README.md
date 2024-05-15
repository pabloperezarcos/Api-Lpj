# Api-Lpj

Este repositorio fue desarrollado con Python y Django para establecer una comunicación con la base de datos en AWS y realizar las operaciones CRUD (Crear, Leer, Actualizar, Eliminar) de nuestro repositorio [RegisterAPP_v2](https://github.com/pabloperezarcos/RegisterAPP_v2).

## Características

- **Tecnologías utilizadas:** Python, Django
- **Funcionalidad principal:** 
  - Conexión a la base de datos alojada en AWS
  - Realización de operaciones CRUD para la aplicación RegisterAPP_v2

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/pabloperezarcos/Api-Lpj.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd Api-Lpj
    ```
3. Crea un entorno virtual:
    ```bash
    python -m venv env
    ```
4. Activa el entorno virtual:
    - En Windows:
        ```bash
        env\Scripts\activate
        ```
    - En macOS/Linux:
        ```bash
        source env/bin/activate
        ```
5. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. Configura la conexión a la base de datos en `settings.py`:
    ```python
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.postgresql',
            'NAME': 'nombre_de_tu_base_de_datos',
            'USER': 'tu_usuario',
            'PASSWORD': 'tu_contraseña',
            'HOST': 'tu_host',
            'PORT': 'tu_puerto',
        }
    }
    ```
2. Realiza las migraciones de la base de datos:
    ```bash
    python manage.py migrate
    ```
3. Inicia el servidor de desarrollo:
    ```bash
    python manage.py runserver
    ```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para cualquier mejora o corrección.

---

¡Gracias por visitar y utilizar Api-Lpj! Si tienes alguna pregunta o sugerencia, no dudes en contactarme.
