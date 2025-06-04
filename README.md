# memorify

Ejemplo básico de inicio de sesión con Django.

## Instalación

1. Crea un entorno virtual y activa.
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta las migraciones y crea un usuario administrador:
   ```bash
   python manage.py migrate
   python manage.py createsuperuser
   ```
4. Inicia el servidor de desarrollo:
   ```bash
   python manage.py runserver
   ```

Accede a `http://localhost:8000/accounts/login/` para ver la pantalla de inicio de sesión.
