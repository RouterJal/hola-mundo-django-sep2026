# Hola Mundo

<div align="center">
  <img src="https://img.shields.io/badge/Django-6.1.1-092E20?style=for-the-badge&logo=django" alt="Django 6.1.1" />
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python" alt="Python" />
  <img src="https://img.shields.io/badge/Status-Ready-28A745?style=for-the-badge" alt="Status" />
</div>

<p align="center">
  <strong>Una pequeña aplicación web construida con Django para mostrar una página inicial con estilo minimalista.</strong>
</p>

---

## ✨ Descripción

Este proyecto es una base ligera de Django para comenzar a desarrollar una aplicación web con una estructura ordenada y lista para personalizar. Incluye una vista principal y una plantilla simple, ideal como punto de partida para nuevos proyectos.

---

## 🧩 Tecnologías utilizadas

- Python
- Django
- SQLite
- HTML + CSS básico

---

## 📁 Estructura del proyecto

```text
hola-mundo/
├── django_base/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── pages/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── templates/
│   └── home.html
├── db.sqlite3
├── manage.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 Instalación

1. Clona el repositorio:

```bash
git clone <url-del-repositorio>
cd hola-mundo
```

2. Crea un entorno virtual:

```bash
python -m venv venv
```

3. Activa el entorno virtual:

- Windows:

```bash
venv\Scripts\activate
```

- macOS/Linux:

```bash
source venv/bin/activate
```

4. Instala las dependencias:

```bash
pip install -r requirements.txt
```

5. Ejecuta las migraciones:

```bash
python manage.py migrate
```

6. Inicia el servidor:

```bash
python manage.py runserver
```

7. Abre tu navegador en:

```text
http://127.0.0.1:8000/
```

---

## 🖥️ Funcionalidad principal

La aplicación cuenta con una vista inicial que renderiza la plantilla `home.html`, mostrando un texto simple y una base mínima que puedes adaptar a tu proyecto.

---

## 🛠️ Comandos útiles

```bash
python manage.py check
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

---

## 📌 Personalización

Puedes modificar:

- La vista en `pages/views.py`
- Las rutas en `pages/urls.py`
- El contenido visual en `templates/home.html`
- La configuración general en `django_base/settings.py`

---

## 🧠 Nota

Este proyecto sirve como base para crear aplicaciones más grandes, agregando modelos, formularios, autenticación, templates avanzados y lógica empresarial según tus necesidades.

---

## 📄 Licencia

Este proyecto se distribuye bajo una licencia de uso libre para fines educativos y de desarrollo personal.

<p align="center">
  <sub>Hecho con ❤️ y Django.</sub>
</p>
