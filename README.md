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