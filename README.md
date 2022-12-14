# SIMPLE PRIVATE API BUILT WITH DJANGO AND VUE

This project was built in a windows environment

- Create a virtual environment
```console
py -m venv ./
```

- Activate virtual environment
```console
source ./Scripts/activate
```

- Install django
```console
pip install django
```

- Start new django project
```console
django-admin startproject djangovueapi
```

- Create a new django application
```console
python djangovueapi/manage.py startapp api
```

- Migrate database
```console
python djangovueapi/manage.py migrate
```

- Run dev server 
```console
python djangovueapi/manage.py runserver
```