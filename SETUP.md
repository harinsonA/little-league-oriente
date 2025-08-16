# Configuración del Proyecto

## Variables de Entorno
Para configuración local, crea un archivo `.env` en la raíz del proyecto con:

```env
DEBUG=True
SECRET_KEY=your-secret-key-here
ALLOWED_HOSTS=localhost,127.0.0.1
DATABASE_URL=sqlite:///db.sqlite3
```

## Comandos Útiles

### Desarrollo
```bash
# Activar entorno virtual
.venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar migraciones
python manage.py migrate

# Crear superusuario
python manage.py createsuperuser

# Ejecutar servidor de desarrollo
python manage.py runserver

# Ejecutar tests
python manage.py test
```

### Git Workflow
```bash
# Crear nueva rama
git checkout -b feature/nueva-funcionalidad

# Hacer commit
git add .
git commit -m "Descripción del cambio"

# Push a la rama
git push origin feature/nueva-funcionalidad

# Merge a main
git checkout main
git pull origin main
git merge feature/nueva-funcionalidad
git push origin main
```

## Estructura de Ramas
- `main`: Rama principal con código estable
- `develop`: Rama de desarrollo (crear cuando sea necesario)
- `feature/*`: Ramas para nuevas funcionalidades
- `hotfix/*`: Ramas para correcciones urgentes
