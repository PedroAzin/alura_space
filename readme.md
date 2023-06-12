## virtualenv = node_modules

Utilizando o módulo virtualenv, podemos separar as dependências de cada projeto.


Desta forma, cada projeto possui suas próprias dependências, não precisando utilizar os módulos no escopo global.

A utilização de ambientes virtuais em projetos Python é uma prática padrão no desenvolvimento de software com a linguagem. O consenso da comunidade Python de que ambientes virtuais são uma ótima prática levou à criação de vários projetos com o objetivo de oferecer versões alternativas de ambientes virtuais e novas formas de gerenciá-los.

- virtualenv venv
- source venv/bin/activate
- deactivate para sair
- pip gerenciador de pacotes 
- pip freeze > requirements.txt

Carregar o django 
- django-admin --help
- django-admin startproject setup .
- python manege.py runserver


Trabalhando com variaveis de ambiente
- pip install python-dotenv
- from dotenv import load_dotenv
  - load_dotenv()
- str(os.getenv('SECRET_KEY'))