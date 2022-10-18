# Django progressbar

Progressbar using Djanog and Celery

## Install and Run

Clone the project

```bash
  git clone https://github.com/husseinshaltout/django_progessbar.git
```

Go to the project directory

```bash
  cd profiles-api
```
## Create virtual environment
```
python -m venv <env_name>
```
## Activate virtual environment
- ### Mac/Linux
    ``` bash
    source ./venv/bin/activate
    ```
- ### Windows
    ``` bash
    venv\Scripts\activate.bat
    ```
    You may need to add full path (c:\users\....venv\Scripts\activate.bat)

## Install requirements

```bash
pip install -r requirements.txt
```

## Run migrations

```bash
python manage.py migrate
```

## Start the development server

```bash
python manage.py runserver 0.0.0.0:8000
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
