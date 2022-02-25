# django-postgreSQL
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/LombaAnderson/django-postgresSQL/blob/main/LICENSE)

# Sobre o projeto
Simples exemplo de início de projeto usando Django, o banco de dados PostgreSQL com Docker. Esse começo de projeto está pronto para dar continuidade a qualquer projeto utilizando Python e
PostgreSQL. Foi adicionado ao exemplo o Python-decouple para esconder as senhas do Django.
 
# Tecnologias utilizadas

- Python
- API Django
- Docker
- Python-decouple( responsável por escamotiar as senhas do Django. Mas se precisar da senha é só me pedir)

# Instruções para compilar, testar e rodar o projeto

```bash
# Clonar repositório
git clone https://github.com/LombaAnderson/django-postgresSQL

# Criação do ambiente de desenvolvimento do Python
-python -m venv venv

# Ativar o ambiente de desenvolvimento(venv)
-source venv/Scripts/activate

# Instalação do Django (Atenção: instalar somente após a ativação da venv)
-pip install django
 
# Comando de criação do projeto
-django-admin startproject docker .

# Criação e acesso ao servidor
-python manage.py runserver

# Acesso ao servidor Django
http://127.0.0.1:8000/accounts/signup/

```

# Autor

Anderson Lomba de Oliveira

Linkedin

https://www.linkedin.com/in/anderson-lomba-140279142/

Portfólio

https://www.lombanderson.epizy.com

# Agradecimentos

Agradeço ao meu Deus que está sempre comigo e a minha esposa, minha companheira que amo muito e sempre torce por mim!
