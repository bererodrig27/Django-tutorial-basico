# Django Tutorial Básico - Proyecto mysite

Repositorio **Tutorial Básico de Django 5.2** según la documentación oficial:  
https://docs.djangoproject.com/en/5.2/

## Estructura del proyecto
```
mysite/
│   manage.py
│
├── mysite/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
└── polls/
    ├── migrations/
    │   └── __init__.py
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── tests.py
    ├── urls.py
    └── views.py
```

## Requisitos previos
- Python 3.10 o superior
- pip (gestor de paquetes de Python)

## Instalación y ejecución
1. Instalar dependencias:
```bash
pip install django
```

2. Realizar migraciones:
```bash
python manage.py migrate
```

3. Ejecutar el servidor:
```bash
python manage.py runserver
```

4. Abrir en el navegador:
- Página principal de polls: http://127.0.0.1:8000/polls/
- Panel de administración: http://127.0.0.1:8000/admin/

## Credenciales de administrador
Para crear un superusuario:
```bash
python manage.py createsuperuser
```

## Créditos
Proyecto basado en el tutorial oficial de Django.
