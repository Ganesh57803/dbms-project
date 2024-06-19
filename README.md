```markdown
# **DBMS Music Library**

A Django project that models a real-world music library, featuring user and admin login, registration, and management of artists, albums, songs, and playlists.

## **Getting Started on Windows**

### Step 1: Activate Virtual Environment

To activate the virtual environment, run the following command in your terminal or command prompt:

```bash
venv\Scripts\activate
```

### Step 2: Install Requirements

To install the required packages, run the following command:

```bash
pip install -r requirements.txt
```

### Step 3: Migrate and Make Migrations

To migrate and make migrations, run the following commands:

```bash
python manage.py makemigrations
python manage.py migrate
```

### Step 4: Create Superuser

To create a superuser, run the following command:

```bash
python manage.py createsuperuser
```

### Step 5: Run Server

To run the server, run the following command:

```bash
python manage.py runserver
```

### Note:
To clear the database, use the following command:

```bash
python manage.py flush
```

**You're all set!**

Your Django project is now up and running! Open a web browser and navigate to `http://localhost:8000` to see the project in action.
