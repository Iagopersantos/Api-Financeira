
<h1 align="center">
 API - Financeira
</h1>


<p align="center">
  <a href="https://nodejs.org/en/" target="blank"><img src="https://vistaran-tech.s3.ap-south-1.amazonaws.com/wp-content/uploads/2022/05/13104926/nodejs-logo.png" width="300" alt="Node Logo" /></a>
</p>

## Installation

```bash
$ npm install
$ yarn
```

## Running the app

```bash
# development
$ npm run dev or yarn dev

# Listening on port
localhost:3333/
```


## REQUISITOS

- [x] Deve ser possível criar uma conta 
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar depósito
- [x] Deve ser possível realizar saque
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [x] Deve ser possível atualizar dados da conta do cliente
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível deletar uma conta
- [x] Deve ser possível retornar o balanço da conta

## Regras de Negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível fazer saque quando saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não existente
- [x] Não deve ser possível retornar o balanço de uma conta não existente
