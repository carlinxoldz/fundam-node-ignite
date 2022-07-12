## FinAPI - Financeira

---

### Modo de inicialização:
- yarn/npm dev

### Requisitos

- [x] Deve ser possivel criar uma conta
- [x] Deve ser possivel buscar o extrato bancário do cliente
- [x] Deve ser possivel realizar um depósito
- [x] Deve ser possivel realizar um saque
- [x] Deve ser possivel buscar o extrato bancário do cliente por data
- [x] Deve ser possivel atualizar dados da conta do cliente
- [x] Deve ser possivel obter dados da conta do cliente
- [x] Deve ser possivel deletar uma conta
- [x] Deve ser possivel retornar o balance

## Regras de negócio

- [x] Não Deve ser possivel cadastrar uma conta com CPF já existente
- [x] Não Deve ser possivel fazer depósito em uma conta não existente
- [x] Não Deve ser possivel buscar extrato em uma conta não existente
- [x] Não Deve ser possivel fazer saque em uma conta não existente
- [x] Não Deve ser possivel excluir uma não existente
- [x] Não Deve ser possivel fazer saque quando o saldo for insuficiente
