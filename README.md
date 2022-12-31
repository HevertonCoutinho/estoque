# Como rodar o projeto?

## Clone esse repositório.
- git clone https://github.com/rg3915/estoque.git

## Crie um virtualenv.
- cd estoque
- pip install --user virtualenv
- py -m venv env

## Ative o virtualenv.
- .\env\Scripts\activate

## Instale as dependências.
- pip install -r requirements.txt

## Rode as migrações.
- python contrib/env_gen.py
- python manage.py migrate
- python manage.py createsuperuser
- python manage.py runserver

## Links

[python-decouple](https://github.com/henriquebastos/python-decouple)

[package-of-the-week-python-decouple](https://simpleisbetterthancomplex.com/2015/11/26/package-of-the-week-python-decouple.html)

[github.com/rg3915/tutoriais django-basic](https://github.com/rg3915/tutoriais/tree/master/django-basic)

[bootstrap starter-template](https://getbootstrap.com/docs/4.0/getting-started/introduction/#starter-template)

[emmet](https://emmet.io/)

[start.html](https://github.com/JTruax/bootstrap-starter-template/blob/master/template/start.html)
