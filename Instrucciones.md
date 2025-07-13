# 🐍 Instalación de Django desde Cero

## 📑 Índice
- [📋 Prerrequisitos](#-prerrequisitos)
- [🪟 Instalación en Windows](#-instalación-en-windows)
- [🍎 Instalación en macOS](#-instalación-en-macos)
- [🐧 Instalación en Linux](#-instalación-en-linux)
- [✅ Verificar la Instalación](#-verificar-la-instalación)
- [🎯 Crear tu Primer Proyecto Django](#-crear-tu-primer-proyecto-django)
- [📁 Estructura del Proyecto Creado](#-estructura-del-proyecto-creado)
- [🌐 Acceder a tu Aplicación](#-acceder-a-tu-aplicación)
- [🛠️ Comandos Útiles](#️-comandos-útiles)
- [🔧 Solución de Problemas Comunes](#-solución-de-problemas-comunes)
- [📚 Recursos Adicionales](#-recursos-adicionales)

---

## 📋 Prerrequisitos

Antes de instalar Django, necesitas tener Python instalado en tu sistema. Selecciona tu sistema operativo:

- [🪟 Windows](#-instalación-en-windows)
- [🍎 macOS](#-instalación-en-macos)  
- [🐧 Linux](#-instalación-en-linux)

---

## 🪟 Instalación en Windows

### 1. 🐍 Instalar Python
1. 📥 Descarga Python desde [python.org](https://www.python.org/downloads/)
2. ⚙️ Ejecuta el instalador y **marca la casilla "Add Python to PATH"**
3. ✅ Verifica la instalación:
```bash
python --version
```

### 2. 📦 Verificar pip
```bash
py -m pip --version
```

### 3. 🚀 Instalar Django

#### Opción A: 🌍 Instalación Global (Recomendada para principiantes)
```bash
py -m pip install Django
```

#### Opción B: 🔒 Instalación en Entorno Virtual (Recomendada para proyectos)
```bash
# 🔧 Crear entorno virtual
py -m venv mi_proyecto_env

# ✅ Activar entorno virtual
mi_proyecto_env\Scripts\activate

# 📦 Instalar Django
pip install Django
```

---

## 🍎 Instalación en macOS

### 1. 🐍 Instalar Python
```bash
# 🍺 Usando Homebrew (recomendado)
brew install python

# 📥 O descarga desde python.org
```

### 2. 📦 Verificar pip
```bash
python3 -m pip --version
```

### 3. 🚀 Instalar Django

#### Opción A: 🌍 Instalación Global (Recomendada para principiantes)
```bash
python3 -m pip install Django
```

#### Opción B: 🔒 Instalación en Entorno Virtual (Recomendada para proyectos)
```bash
# 🔧 Crear entorno virtual
python3 -m venv mi_proyecto_env

# ✅ Activar entorno virtual
source mi_proyecto_env/bin/activate

# 📦 Instalar Django
pip install Django
```

---

## 🐧 Instalación en Linux

### 1. 🐍 Instalar Python
```bash
# Ubuntu/Debian
sudo apt update
sudo apt install python3 python3-pip

# CentOS/RHEL/Fedora
sudo dnf install python3 python3-pip
# O
sudo yum install python3 python3-pip
```

### 2. 📦 Verificar pip
```bash
python3 -m pip --version
```

### 3. 🚀 Instalar Django

#### Opción A: 🌍 Instalación Global (Recomendada para principiantes)
```bash
python3 -m pip install Django
```

#### Opción B: 🔒 Instalación en Entorno Virtual (Recomendada para proyectos)
```bash
# 🔧 Crear entorno virtual
python3 -m venv mi_proyecto_env

# ✅ Activar entorno virtual
source mi_proyecto_env/bin/activate

# 📦 Instalar Django
pip install Django
```

---

## ✅ Verificar la Instalación

```bash
# 🔍 Verificar versión de Django
python -m django --version

# 🔍 O
django-admin --version
```

---

## 🎯 Crear tu Primer Proyecto Django

```bash
# 🏗️ Crear un nuevo proyecto
django-admin startproject mi_proyecto

# 📁 Navegar al directorio del proyecto
cd mi_proyecto

# 🚀 Ejecutar el servidor de desarrollo
python manage.py runserver
```

---

## 📁 Estructura del Proyecto Creado

```
📂 mi_proyecto/
├── ⚙️ manage.py
└── 📂 mi_proyecto/
    ├── 📄 __init__.py
    ├── ⚙️ settings.py
    ├── 🔗 urls.py
    ├── 🌐 asgi.py
    └── 🌐 wsgi.py
```

---

## 🌐 Acceder a tu Aplicación

1. 🌍 Abre tu navegador
2. 🔗 Ve a `http://127.0.0.1:8000/` o `http://localhost:8000/`
3. ✅ Deberías ver la página de bienvenida de Django

---

## 🛠️ Comandos Útiles

```bash
# 🆕 Crear una nueva aplicación
python manage.py startapp mi_aplicacion

# 📝 Crear migraciones
python manage.py makemigrations

# 🔄 Aplicar migraciones
python manage.py migrate

# 👤 Crear superusuario
python manage.py createsuperuser

# 🧪 Ejecutar tests
python manage.py test
```

---

## 🔓 Desactivar Entorno Virtual

```bash
deactivate
```

---

## 🔧 Solución de Problemas Comunes

### ❌ Error: "python no se reconoce como comando"
- ✅ Asegúrate de que Python esté en el PATH
- 🪟 En Windows, usa `py` en lugar de `python`

### ❌ Error: "pip no se reconoce como comando"
- 📦 Instala pip: `python -m ensurepip --upgrade`
- 🪟 En Windows, usa: `py -m pip`

### ❌ Error de permisos en Linux/macOS
- 🔐 Usa `sudo` para instalaciones globales
- 🔒 O mejor aún, usa entornos virtuales

---

## 📚 Recursos Adicionales

- 📖 [Documentación oficial de Django](https://docs.djangoproject.com/)
- 🎓 [Tutorial oficial de Django](https://docs.djangoproject.com/en/stable/intro/tutorial01/)
- 📋 [Guía de instalación oficial](https://docs.djangoproject.com/en/stable/howto/installation/)


