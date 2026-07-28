# 📚 Jogoteca - Flask Web App

Aplicação web desenvolvida com **Flask** para gerenciamento de jogos, com sistema de autenticação de usuários e controle de acesso para criação de novos jogos.

---

## 🚀 Tecnologias utilizadas

- Python 🐍
- Flask
- HTML5 + Jinja2
- Bootstrap

---

## 🎮 Funcionalidades

- 📋 Listagem de jogos
- ➕ Cadastro de novos jogos
- 🔐 Sistema de login
- 🚫 Proteção de rotas (necessário estar logado)
- 🔓 Logout de usuário
- 💬 Mensagens com Flash

---

## 🔑 Autenticação

A aplicação possui um sistema simples de login utilizando sessão (session do Flask).

### Usuários disponíveis para teste:

| Usuário | Senha |
|--------|------|
| adm    | 123 |
| Mila   | paozinho |
| Cake   | Python_eh_vida |

---

## 🛠️ Como rodar o projeto

### 1. Clone o repositório
```
  git clone https://github.com/VMurtis/flask-webapp-jogoteca.git

```
---

### 2. Acesse a pasta do projeto
```
  cd flask-webapp-jogoteca
```
---

### 3. Crie um ambiente virtual
```
  python -m venv venv
```
---

### 4. Ative o ambiente

Windows
```
venv\Scripts\activate
```
---
Linux/Mac
```
source venv/bin/activate
```
---

### 5. Instale as dependências
pip install flask

---

### 6. Execute a aplicação

python jogoteca.py

---

## 🌐 Acesse no navegador
```
http://127.0.0.1:5000/
```
---

## 🔒 Controle de acesso

- A rota `/novo` é protegida  
- Usuários não autenticados são redirecionados para a página de login  
- Após autenticação, o usuário retorna automaticamente para a página que tentou acessar  

---

## 📁 Estrutura do projeto

<img width="248" height="418" alt="image" src="https://github.com/user-attachments/assets/421e699c-faf1-4c3a-ad77-f9b27e50a14b" />
