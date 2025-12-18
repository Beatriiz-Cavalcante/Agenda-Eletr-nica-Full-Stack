# 📅 Agenda Eletrônica – Full Stack

Projeto desenvolvido como **desafio técnico**, com o objetivo de demonstrar conhecimentos em **React JS**, **Node.js (Express)**, **MySQL** e boas práticas de desenvolvimento web.

A aplicação permite que usuários se cadastrem, façam login e gerenciem suas próprias atividades em uma agenda eletrônica, com visualização em formato de calendário.

---

## 🚀 Tecnologias Utilizadas

### 🔧 Backend

* Node.js
* Express
* Sequelize (ORM)
* MySQL
* JWT (autenticação)
* bcrypt (criptografia de senha)

### 🎨 Frontend

* React JS
* Material UI
* FullCalendar
* Axios

---

## 📌 Funcionalidades

### 👤 Usuários

* Cadastro de usuário
* Login com autenticação JWT
* Cada usuário visualiza apenas suas próprias atividades

### 🗓️ Atividades

* Criar atividade
* Listar atividades
* Editar atividade
* Excluir atividade
* Alterar status (pendente, concluída, cancelada)
* Visualização das atividades em calendário

---

## ⚙️ Pré-requisitos

Antes de rodar o projeto, certifique-se de ter instalado:

* Node.js (versão LTS)
* MySQL
* Git

---

## 🔧 Configuração do Backend

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/seuusuario/agenda-app.git
```

### 2️⃣ Acesse a pasta do backend

```bash
cd agenda-app/backend
```

### 3️⃣ Instale as dependências

```bash
npm install
```

### 4️⃣ Configure o banco de dados

Crie um banco de dados no MySQL:

```sql
CREATE DATABASE agenda_db;
```

Configure a conexão no arquivo:

```text
src/config/database.js
```

### 5️⃣ Execute o servidor

```bash
npm start
```

O Sequelize criará automaticamente as tabelas necessárias.

---




