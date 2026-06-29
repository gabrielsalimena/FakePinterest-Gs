# FakePinterest

Clone do Pinterest desenvolvido em Flask (Python) como projeto de estudo, com cadastro/login de usuários, upload de fotos e feed de posts.

## Funcionalidades

Cadastro e login de usuários (Flask-Login + Flask-Bcrypt para hash de senha), upload de fotos de perfil, feed com posts ordenados por data de criação e página de perfil de usuário.

## Tecnologias

Python, Flask, Flask-SQLAlchemy (banco de dados), Flask-Login e Flask-Bcrypt (autenticação), Flask-WTF (formulários), SQLite, HTML e CSS.

## Como executar

Instale as dependências, crie o banco de dados e execute a aplicação:

```bash
pip install flask flask-sqlalchemy flask-login flask-bcrypt flask-wtf
python criar_banco.py
python main.py
```

A aplicação cria o banco de dados local (instance/comunidade.db) na primeira execução do criar_banco.py.

## Estrutura

fakepinterest/ contém a aplicação Flask (models, forms, rotas). Layout/ e fakepinterest/templates contêm os templates HTML. main.py é o ponto de entrada da aplicação. criar_banco.py é o script para criação do banco de dados.
