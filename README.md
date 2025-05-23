# Virtual-environment-initialization
---------- Criar arquivo ------------

# Setting up and activating the virtual environment
1º python -m venv .venv
2º .venv\Scripts\activate.bat
3º py -m pip install Django
4º django-admin startproject todoApp

# In a duplicated terminal
**** Dentro do Arquivo inicial ******

5º .venv\Scripts\activate.bat
6º cd todoApp
7º python manage.py migrate
8º python manage.py createsuperuser

******* Nome de usuário **************
*******     Email       **************
*******     Senha       **************

9º python manage.py start todo_list



