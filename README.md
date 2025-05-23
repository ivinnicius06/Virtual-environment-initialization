# Virtual-environment-initialization
---------- Criar arquivo ------------

1º python -m venv .venv
2º .venv\Scripts\activate.bat
3º py -m pip install Django
4º django-admin startproject todoApp

----- Em um terminal duplicado ------
**** Dentro do Arquivo inicial ******

5º .venv\Scripts\activate.bat
6º cd todoApp
7º python manage.py migrate
8º python manage.py createsuperuser

******* Nome de usuário **************
*******     Email       **************
*******     Senha       **************

9º python manage.py start todo_list

# Segunda etapa

