# project_blog (Django Project)

This repository contains a Django project named `project_blog`.

## Prerequisites

- Python 3.11+
- Git (optional)

## 1. Clone and move into the project

```powershell
git clone <your-repo-url>
cd django-HIT237-2026-week2-practicals
```

## 2. Create and activate a virtual environment

Create the environment:

```powershell
python -m venv .venv
```

Activate on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Activate on Windows Command Prompt:

```cmd
.venv\Scripts\activate.bat
```

## 3. Install dependencies

```powershell
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## 4. Initialize the database

```powershell
python manage.py migrate
```

## 5. Run the development server

```powershell
python manage.py runserver
```

Open `http://127.0.0.1:8000/` in your browser.

## Project Notes

- Project name: `project_blog`
- No Django app has been added yet (project scaffold only).
- Default database: SQLite (`db.sqlite3`).
