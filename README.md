# 📋 Gestor de Tareas

Una aplicación web sencilla para gestionar tareas y clientes, pensada para emprendedores, freelancers o pequeños negocios que necesiten organizar su trabajo.

## 🚀 Características

- Registro y administración de clientes
- Creación, edición y eliminación de tareas
- Asignación de tareas a clientes
- Cambiar estado de tareas: pendiente, en proceso, finalizada
- Visualización de estadísticas simples
- Sistema de login con autenticación

## 🛠️ Tecnologías utilizadas

- HTML, CSS, JavaScript (Frontend)
- Python con Flask (o Django) – Backend
- SQLite (o PostgreSQL) – Base de datos
- Bootstrap – Estilos responsivos
- Jinja2 – Plantillas dinámicas

## 🧑‍💻 Cómo instalar y ejecutar

1. Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/gestor-tareas.git
cd gestor-tareas
```

2. Crea y activa un entorno virtual (opcional pero recomendado):

```bash
python -m venv env
source env/bin/activate   # En Windows usa: env\Scripts\activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Ejecuta la aplicación:

```bash
python app.py
```

5. Abre tu navegador en http://localhost:5000/

## 📁 Estructura del proyecto
```bash
gestor-tareas/
│
├── app.py
├── static/
│   └── estilos.css
├── templates/
│   ├── index.html
│   ├── login.html
│   └── dashboard.html
├── models/
│   └── models.py
├── requirements.txt
└── README.md
```
## 🔐 Acceso

Usuario demo: admin@example.com

Contraseña: admin123

⚠️ Importante: cambia las credenciales en producción.

## 📈 Futuras mejoras

- Exportación de tareas en PDF/Excel
- Notificaciones por correo o WhatsApp
- Asignación de prioridades a tareas
- Multiusuario con roles

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Ver archivo LICENSE.

Hecho con ❤️ por MayraMoy
