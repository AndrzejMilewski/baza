# 📦 Projekt Django — Baza użytkowników

Prosty projekt Django z obsługą logowania, rejestracji i bazą SQL.

---

## 🚀 Wymagania

- Python 3.10+ (sprawdź poleceniem `python --version`)
- Git
- Virtualenv (opcjonalne, ale zalecane)

---

## 📥 Instalacja

1. **Sklonuj repozytorium**
   ```bash
   git clone https://github.com/<twoj-login>/<twoj-projekt>.git
   cd <twoj-projekt>
   ```

python -m venv venv

# Windows

.\venv\Scripts\activate

# Linux/Mac

source venv/bin/activate

pip install -r requirements.txt


python manage.py migrate


python manage.py createsuperuser


python manage.py runserver


http://127.0.0.1:8000
