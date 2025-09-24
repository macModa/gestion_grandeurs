"# gestion_grandeurs" 
Perfect 👍 Here’s a README.md template you can copy-paste into your project. It explains how to set up the environment after cloning your Django project:

# Gestion Grandeurs

Django project for managing and visualizing IoT sensor data.

## 🚀 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/macModa/gestion_grandeurs.git
cd gestion_grandeurs

2. Create a virtual environment
python -m venv .venv

3. Activate the environment

Windows (PowerShell):

.venv\Scripts\activate


Linux / MacOS:

source .venv/bin/activate

4. Install dependencies

Make sure you have requirements.txt in the repo. Then run:

pip install -r requirements.txt

5. Run database migrations

Since db.sqlite3 is ignored in Git, you need to initialize it locally:

python manage.py migrate

6. Create a superuser (optional, for Django Admin)
python manage.py createsuperuser

7. Run the development server
python manage.py runserver


Then open your browser at http://127.0.0.1:8000/
.
