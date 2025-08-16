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
- `documentacion/`: Documentación técnica y seguimiento del proyecto
- `manage.py`: Herramienta de línea de comandos de Django
- `requirements.txt`: Dependencias del proyecto
- `.venv/`: Entorno virtual (no incluir en control de versiones)

## 📋 Documentación del Proyecto

Para información detallada sobre el estado y planificación del proyecto, consulta la carpeta [`documentacion/`](./documentacion/):

- **[Estado del Proyecto](./documentacion/estado-del-proyecto.md)**: Seguimiento de tareas completadas y pendientes
- **[Planificación de Sprints](./documentacion/planificacion-sprints.md)**: Cronograma detallado de desarrollo
- **[Guía de Documentación](./documentacion/README.md)**: Cómo usar y mantener la documentación

## Estado del Proyecto

- ✅ **Configuración inicial de Django** - Proyecto base funcionando
- ✅ **Entorno virtual configurado** - Entorno aislado para dependencias
- ✅ **Base de datos SQLite configurada** - BD de desarrollo lista
- ✅ **Superusuario creado** - Acceso al panel de administración
- ✅ **Control de versiones** - Repositorio Git conectado a GitHub
- ✅ **Documentación inicial** - Sistema de seguimiento implementado
- 🔄 **Próximos pasos**: Análisis de requerimientos y diseño de modelos

**Progreso general**: 15% completado | **Próximo hito**: Estructura de Datos

## Contribución

Este proyecto está en desarrollo inicial. Las contribuciones serán bienvenidas una vez establecida la estructura base.
