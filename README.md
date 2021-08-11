# django-simples

Aprendendo a criar um projeto simples com Django

## Como rodar o projeto

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

...
git clone https://github.com/progmuito/django-simples.git
cd django-simples
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
...