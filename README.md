# Crymzee Assessment (Python-Django)

## What is this project?
A simple web app where users can:
- Register (with email, password, and date of birth)
- Log in and log out
- Upload, view, download, and delete their own files (with title and description)

## Quick Start

1. **Clone this repo**
   ```bash
   git clone git@github.com:DanishKhan-pixel/Crymzee_-assessment.git
   ```
2. **Create a virtual environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run migrations**
   ```bash
   python manage.py migrate
   ```
5. **Start the server**
   ```bash
   python manage.py runserver
   ```

## Tech Used
- Python, Django 5
- SQLite (default database)

## File Uploads
- Files are stored in the `media/uploads/` folder.

## For Admin
- To access Django admin, create a superuser:
  ```bash
  python manage.py createsuperuser
---

**If you get stuck, make sure you have Python 3 and Django installed.**
