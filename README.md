# Django start template
### This is django start template
What has this template:
1. Degub tools
2. Django Compressor
3. Settings file is configurated

### How to start:
```
python3 -m venv venv

. venv/bin/activate

pip3 install -r requirements.txt

python3 manage.py collectstatic

python3 manage.py migrate

python3 manage.py createsuperuser

python3 manage.py runserver
```