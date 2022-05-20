### API Finance

API construída durante o curso de Node.js no Ignite da Rocketseat, possuindo requisitos, bem como regras de negócio a serem seguidas.

- Tecnologias: Node.js, Express, Nodemon, uuid.
- Contém os métodos GET, POST, PUT, DELETE (CRUD);
- Utiliza o recurso de middleware.
- O projeto está configurado para ser rodado na porta 3333.

## Requisitos:

- [x] Deve ser possível criar uma conta;
- [x] Deve ser possível buscar o extrato bancário do cliente;
- [x] Deve ser possível realizar um depósito;
- [x] Deve ser possível realizar um saque;
- [x] Deve ser possível buscar o extrato bancário do cliente por data;
- [x] Deve ser possível atualizar dados da conta do cliente;
- [x] Deve ser possível obter dados da conta do cliente;
- [x] Deve ser possível deletar uma conta;
- [x] Deve ser possível retornar o balanço da conta do cliente.


## Regras de negócio:

- [x] Não deve ser possível cadastrar uma conta com CPF já existente;
- [x] Não deve ser possível buscar extrato em uma conta não existente;
- [x] Não deve ser possível fazer depósito em uma conta não existente;
- [x] Não deve ser possível fazer saque em uma conta não existente;
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente;
- [x] Não deve ser possível retornar o balanço de uma conta não existente;
- [x] Não deve ser possível excluir uma conta não existente;