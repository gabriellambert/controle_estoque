# controle_estoque

Controle de estoque

## Como rodar o projeto?

* Clone esse repositório
* Crie uma virtualenv com Python3
* Ative a virtualenv
* Instale as dependências
* Rode as migrações
```
git clone https://github.com/gabriellambert/controle_estoque.git
cd controle_estoque
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```