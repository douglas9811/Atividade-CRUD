# 📚 Sistema de Matrícula – CRUD em Django

## 🚀 Tecnologias Utilizadas
- Python 3.13+
- Django 5.x
- Bootstrap 5 (para estilização dos templates)

## 📌 Funcionalidades
- Cadastro de alunos
- Listagem de alunos com status (Ativo/Inativo) e destaque por turno
- Visualização detalhada das informações do aluno
- Edição de dados do aluno
- Exclusão de aluno com confirmação

## 🛠️ Estrutura de Dados do Aluno

### Informações Pessoais
- Nome
- CPF
- RG
- Data de Nascimento
- Sexo

### Contato
- E-mail
- Telefone
- Telefone de emergência

### Endereço
- CEP
- Endereço
- Número
- Complemento
- Bairro
- Cidade
- UF

### Acadêmico
- Número de matrícula
- Curso
- Série/Ano
- Turno
- Status (Ativo/Inativo)
- Observações

## ▶️ Como Rodar o Projeto

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/seu-usuario/matricula.git
cd matricula
2️⃣ Criar e ativar o ambiente virtual
Windows

bash
Copy code
python -m venv venv
venv\Scripts\activate
Linux/Mac

bash
Copy code
python -m venv venv
source venv/bin/activate
3️⃣ Instalar dependências
bash
Copy code
pip install -r requirements.txt
4️⃣ Migrar o banco de dados
bash
Copy code
python manage.py migrate
5️⃣ Rodar o servidor
bash
Copy code
python manage.py runserver
O sistema estará disponível em: http://127.0.0.1:8000
