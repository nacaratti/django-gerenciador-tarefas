# django-gerenciador-tarefas
### Projeto básico para um gerenciador de tarefas

### Cloning the repository

--> Clone the repository using the command below :
```bash
git clone https://github.com/nacaratti/django-gerenciador-tarefas

```

--> Move into the directory where we have the project files : 
```bash
cd django-gerenciador-tarefas

```

--> Create a virtual environment :
```bash
# Create our virtual environment
python -m venv .venv

```

--> Activate the virtual environment : <br><br>
windows
```bash
.venv\Scripts\activate

```

--> Install the requirements :
```bash
pip install -r requirements.txt

```

--> Create Migrations
```bash
python manage.py makemigrations

```

--> Migrate Database
```bash
python manage.py migrate

```

--> Create Super User
```bash
python manage.py createsuperuser

```

#

### Running the App

--> To run the App, we use :
```bash
python manage.py runserver

```

> ⚠ Then, the development server will be started at http://127.0.0.1:8000/
