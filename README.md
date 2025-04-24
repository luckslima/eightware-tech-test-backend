# Backend - Eightware Tech Test

Este é o backend da aplicação desenvolvida para o teste técnico da Eightware. Ele foi construído com **Ruby on Rails 7.2** e utiliza **Devise** com **JWT** para autenticação.

---

## 🚀 Como rodar o projeto:

### 1️⃣ Pré-requisitos

- **Ruby**: versão 3.2.2
- **Rails**: versão 7.2.2

### 2️⃣ Configuração do ambiente

1. Clone o repositório:
   ```bash
   git clone https://github.com/luckslima/eightware-tech-test-backend.git
   cd backend

2. Instale as dependências:
   ```bash
   bundle install

3. Configure o banco de dados:
   ```bash
   rails db:create db:migrate

4. Inicie o servidor:
   ```bash
   rails s

obs: O backend estará disponível em: http://localhost:4567

## 🧪 Como rodar os testes

1. Execute os testes com o RSpec:
   ```bash
   rspec

2. Cobertura dos testes:

- Testes de criação de usuário (/users/signup).
- Testes de login (/users/login).
- Testes da rota /users/me com e sem token JWT.

## 📚 Endpoints disponíveis

### POST /users/signup

- Cria um novo usuário e retorna um token JWT.

### POST /users/login

- Realiza login e retorna um token JWT.

### GET /users/me

- Retorna os dados do usuário autenticado.
- Requer autenticação via JWT.

## 🛠️ Tecnologias utilizadas

- Ruby on Rails 7.2
- Devise- JWT (devise-jwt)
- RSpec

## 📄 Licença

Este projeto é apenas para fins de avaliação técnica.