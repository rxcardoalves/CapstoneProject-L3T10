# Django Capstone Project

## Setup with Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## Run with Docker

```bash
docker build -t mycapstone .
docker run -p 8000:8000 mycapstone
```

Then open:
http://localhost:8000

---

## Environment Variables / Secrets

This project may require secrets such as:

- Django SECRET_KEY
- Database credentials

Create a `.env` file and add them manually.
Do NOT commit this file.