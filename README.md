# Liga de Baseball Little League Oriente - Sistema de Administración

Este es un sistema de administración web desarrollado en Django para gestionar la Liga de Baseball Little League Oriente.

## Instalación y Configuración

### Requisitos Previos

- Python 3.8 o superior

### Configuración del Entorno de Desarrollo

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/harinsonA/little-league-oriente.git
   cd little-league-oriente
   ```

2. **Activar el entorno virtual**

   En Windows:

   ```cmd
   .venv\Scripts\activate
   ```

   En Linux/Mac:

   ```bash
   source .venv/bin/activate
   ```

3. **Instalar dependencias**

   ```bash
   pip install -r requirements.txt
   ```

4. **Ejecutar migraciones**

   ```bash
   python manage.py migrate
   ```

5. **Crear superusuario** (opcional)

   ```bash
   python manage.py createsuperuser
   ```

6. **Ejecutar el servidor de desarrollo**
   ```bash
   python manage.py runserver
   ```

El sistema estará disponible en: http://127.0.0.1:8000/

## Panel de Administración

Accede al panel de administración en: http://127.0.0.1:8000/admin/

**Credenciales por defecto:**

- Usuario: admin
- Contraseña: admin

## Estructura del Proyecto

- `liga_baseball_admin/`: Configuración principal del proyecto Django
- `manage.py`: Herramienta de línea de comandos de Django
- `requirements.txt`: Dependencias del proyecto
- `.venv/`: Entorno virtual (no incluir en control de versiones)

## Estado del Proyecto

- ✅ Configuración inicial de Django
- ✅ Entorno virtual configurado
- ✅ Base de datos SQLite configurada
- ✅ Superusuario creado
- 🔄 **Próximos pasos**: Desarrollo de modelos y aplicaciones específicas

## Contribución

Este proyecto está en desarrollo inicial. Las contribuciones serán bienvenidas una vez establecida la estructura base.
