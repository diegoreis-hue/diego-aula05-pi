Aula da Thati dia 24/03

* criar uma pasta e organizar o projeto
* configuração virtual em envioment.
* instalar o django
* criar um projeto django inicial
* executar o servidor de desenvolvimento


Por que criar uma pasta do projeto? para organizar e deixar tudo dentro da pasta do projeto para não se bagunçar


agora criamos o ambiente virtual no terminal e trabalhamos dentro dele:


Microsoft Windows [versão 10.0.26200.8037]
(c) Microsoft Corporation. Todos os direitos reservados.

C:\Users\202410210006>cd Documents

C:\Users\202410210006\Documents> mkdir django_aulas

C:\Users\202410210006\Documents>cd django_aulas

C:\Users\202410210006\Documents\django_aulas>


Ambiente virtual:
usamos o venv: python -m venv venv
C:\Users\202410210006\Documents\django_aulas>venv\scripts\activate


instalação do django:


(venv) C:\Users\202410210006\Documents\django_aulas>django-admin --version
'django-adimin' não é reconhecido como um comando interno
ou externo, um programa operável ou um arquivo em lotes.( deu errado por que não tinha o django instalado)

(venv) C:\Users\202410210006\Documents\django_aulas>pip install django ( instalou o django)

depois usamos de novo o django-admin --version para ver a versão. o resultado foi:  5.2.12


criação da estrutura do projeto django:


(venv) C:\Users\202410210006\Documents\django_aulas>django-admin startproject reis

(venv) C:\Users\202410210006\Documents\django_aulas>cd reis

criamos um projeto e damos um nome a ele. e depois entramos no nosso projeto  

depois nos usamos o código (code .) para entrar no python.

dentro do python usamos as teclas (ctrl + ') para acessar um terminal la no python. dentro desse terminal eu usei o codigo (python manage.py runserver).
depois que nos foi dado o resultado dessa consulta no python ele nos deu alguns links, e entramos no link (Starting development server at http://127.0.0.1:8000/) que nos levou a um site.

depois entramos no github e criamos um commit dentro de um file (configuracao.md) e colocamos um passo a passo do que foi feito em aula.


