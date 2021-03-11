# FinAPI - Financeira

## 📚 Indice
- [Sobre](#-sobre)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como baixar o projeto](#-como-baixar-o-projeto)
- [Desenvolvimento](#-desencolvimento)

## 📑 Sobre

O projeto **FinAPI** é uma aplicação que realiza a criação, consulta, atualização e destruição (CRUD) de um serviço de contas bancárias. Esse projeto foi deseonvolvido durante o **Bootcamp Ignite** da Rocketseat.

## 💻 Tecnologias utilizadas

- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)

## 💾 Como baixar o projeto

```bash
# Clonar o repositório
$ git clone https://github.com/brunoribeiro-py/finapi.git

# Acessar o diretório
$ cd finapi

# Instalar as dependências do projeto
$ yarn install

# Iniciar o projeto
$ yarn dev

```
Por padrão a aplicação roda no endereço http://localhost:3333.
## 📐 Desenvolvimento

### 👨🏼‍💻 Requisitos

- [x] Deve ser possível criar uma conta
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [x] Deve ser possível atualizar dados da conta do cliente
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível deletar uma conta
- [x] Deve ser possível consultar o saldo da conta

## 📊 Regras de negócio

- [x] Não deve ser possível cadastrar um CPF já existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível buscar extrato em uma conta nao existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não existente

-----
Desenvolvido por Bruno Ribeiro.