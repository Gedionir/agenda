📒 Agenda Django – Sistema de Contatos
✨ Funcionalidades
Cadastro, edição, listagem e exclusão de contatos (CRUD básico).

Cada contato pode conter:

Nome completo

Telefone

E-mail

Endereço (opcional)

Data de criação

Interface administrativa do Django para gerenciar os dados de forma fácil.

Banco de dados SQLite (padrão do Django) para simplicidade e portabilidade.

🛠️ Tecnologias utilizadas
Python 3.x

Django 2.x (ou a versão utilizada na época)

SQLite (banco de dados)

HTML5, CSS3 (básico, com templates do Django)

Bootstrap (se tiver usado) – opcional, ajuste conforme seu projeto

🚀 Como executar o projeto localmente
Pré-requisitos
Python 3 instalado

pip (gerenciador de pacotes do Python)

virtualenv (recomendado)

Passo a passo
Clone o repositório

bash
git clone https://github.com/seu-usuario/agenda-django.git
cd agenda-django
Crie e ative um ambiente virtual

bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate      # Windows
Instale as dependências

bash
pip install -r requirements.txt
Se não houver um arquivo requirements.txt, instale o Django manualmente:

bash
pip install django
Execute as migrações do banco de dados

bash
python manage.py migrate
Crie um superusuário para acessar o admin

bash
python manage.py createsuperuser
Inicie o servidor de desenvolvimento

bash
python manage.py runserver
Acesse no navegador

Aplicação principal: http://127.0.0.1:8000/

Painel administrativo: http://127.0.0.1:8000/admin
