# Backend – Instalación
Proyecto backend desarrollado con **Python 3.13.7** y **FastAPI**.

## Requisitos previos

Antes de comenzar, asegúrate de tener instalados:

- **Python 3.13.7**
- **Pip**
- **Git** (opcional)

Verifica tu versión de Python con:

```bash
python --version
```

## 📥 1. Clonar el repositorio (opcional)

```bash
git clone https://tu-repo.git
cd backend
```

## 🧱 2. Crear y activar un entorno virtual

### ✔ Windows
```bash
python -m venv venv
venv\Scripts\activate
```

### ✔ Linux / Mac
```bash
python3 -m venv venv
source venv/bin/activate
```

## 📦 3. Instalar dependencias

Asegúrate de tener el archivo **requirements.txt** y ejecuta:

```bash
pip install -r requirements.txt
```

## ▶ 4. Ejecutar el servidor FastAPI

```bash
uvicorn app.main:app --reload
```

Acceso:

- API: http://localhost:8000
- Swagger: http://localhost:8000/docs
- ReDoc: http://localhost:8000/redoc

## 5. Desactivar el entorno virtual

```bash
deactivate
```

## Notas finales

- Usa siempre **Python 3.13.7**.
- Instala dependencias desde `requirements.txt`.
- Incluye `requirements.txt` si vas a desplegar el proyecto.
