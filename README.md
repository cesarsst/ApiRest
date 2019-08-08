# ApiRest (Tutorial no windows) 
Exemplo de um Projecto com Django Rest-Framework

## Passos para testes
Requisitos:
  Ter Python 3 instalado na maquina
  Ter o pip instalado

1- Clone o repositorio para sua maquina

2- Abra o CMD e navegue até a pasta
    
    cd <caminho>\ApiRes
   
3- Crie um ambiente virtual e ative-a
  
    python -m vevn venv 
    cd venv
    cd Script
    activate
    cd ..
    cd ..
    
    
4- Instale o Django e o Django-Framework 
     
     pip install django
     pip install djangorestframework
     
 5- Entre na pasta tutorial e rode o servidor

    cd tutorial
    python manage.py runserver
  
  6- Acesse o link para testar alguns metodos
  
      http://127.0.0.1:8000/snippets/
 
Voce Pode fazer acesso usando os metodos com o Postman para testar se quiser. Leia mais em https://www.django-rest-framework.org/api-guide/routers/#defaultrouter para saber como fazer as requisições. 
