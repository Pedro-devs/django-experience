## Integrantes
*Pedro Henrique Andreatti
*Guilherme Max Pereira
*Bruna Bravo

## Este projeto foi feito com:

* [Python 3.10.4](https://www.python.org/)
* [Django 4.0.4](https://www.djangoproject.com/)
* [Django Rest Framework 3.12.4](https://www.django-rest-framework.org/)
* [Bootstrap 4.0](https://getbootstrap.com/)
* [htmx 1.6.1](https://htmx.org/)

## Como rodar o projeto?
* PRIMEIRO BAIXAR ARQUIVO WINRAR E DESCOMPACTAR
* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

##LINK DO REPLIT 
*https://replit.com/@pedrohenriquean/Projeto-python?v=1

```
git clone https://github.com/Pedro-devs/django-experience.git
cd django-experience
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
python manage.py createsuperuser --username="admin" --email=""
```
