# Django Capstone Project

## Clone the Repository

```bash
git clone https://github.com/rxcardoalves/CapstoneProject-L3T10.git
cd myCapstoneSite
```

---

# Run with Virtual Environment

```bash
python -m venv venv

# Windows
venv\Scripts\activate

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

Open:
http://127.0.0.1:8000

---

# Run with Docker

```bash
docker build -t mycapstonesite .
docker run -p 8000:8000 mycapstonesite
```

Open:
http://localhost:8000

---

# User Access

The application includes admin user registration.

You can log in with this test user account:
Username: hypdev2
Password: RS24060015065


```bash
python manage.py createsuperuser
```

Login at:
http://127.0.0.1:8000/admin
