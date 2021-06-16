# django-docker-postgres
Criando um container com docker de aplicação web em django integrado com banco de dados postgresql

# 1. Ter o docker e o docker-compose instalados

links para instalação:

    Docker:
    https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04-pt

    docker-compose:
    pip install docker-compose

# 2. Criando e ativando o ambiente virtual

    pipenv shell

# 3. Instalando o Django e o adaptador para acessar o banco de dados 

    pipenv install django

    pipenv install psycopg2-binary

# 4. Mantendo as dependências fixas em um arquivo requirements.txt

    pipenv lock --keep-outdated --requirements > requirements.txt

# 5. Criando o projeto

    django-admin startproject myproject .



