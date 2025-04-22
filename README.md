 PostgrePy

Projeto em Python com integração ao banco de dados PostgreSQL. Idealizado para aprendizado e prática de manipulação de dados relacionais usando bibliotecas nativas e conexão direta com o banco.

## 📚 Descrição

Este projeto demonstra como conectar uma aplicação Python ao PostgreSQL utilizando `psycopg2`. Inclui operações básicas de CRUD (Create, Read, Update, Delete) em uma tabela simples, simulando o gerenciamento de dados de usuários ou alunos.

## 🚀 Tecnologias Utilizadas

- Python 3.10+
- PostgreSQL
- Psycopg2
- (opcional) Docker

## 📁 Estrutura do Projeto

postgrepy/ ├── db/ │ ├── connection.py # Conexão com o banco │ ├── create_tables.sql # Scripts de criação │ └── ... ├── main.py # Arquivo principal └── README.md

bash
Copiar
Editar

## 💻 Como Rodar

### Pré-requisitos

- Python 3.10 ou superior
- PostgreSQL instalado
- Banco e usuário criados

### Passos:

```bash
# Clone o repositório
git clone https://github.com/crsouza993/postgrepy.git
cd postgrepy

# Crie um ambiente virtual
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows

# Instale dependências
pip install -r requirements.txt

# Configure seu banco no arquivo db/connection.py
# Execute o projeto
python main.py
🎯 Objetivo
Explorar práticas de banco de dados relacionais com PostgreSQL, integração com Python e estruturação de projetos para sistemas mais robustos.
