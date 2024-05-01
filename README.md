# Otimizando o Sistema Bancário com Funções Python

Este projeto consiste na implementação de um sistema bancário simplificado utilizando funções em Python. O sistema oferece funcionalidades básicas como depósito, saque, exibição de extrato, criação de novos usuários e criação de novas contas.

## Funcionalidades Implementadas

### 1. Funções Principais

- `menu()`: Exibe um menu interativo com opções para realizar operações bancárias.
- `depositar(saldo, valor, extrato)`: Realiza um depósito na conta bancária.
- `sacar(saldo, valor, extrato, limite, numero_saques, limite_saques)`: Realiza um saque na conta bancária, considerando limites de saldo e quantidade de saques.
- `exibir_extrato(saldo, extrato)`: Exibe o extrato da conta bancária.
- `criar_usuario(usuarios)`: Cria um novo usuário no sistema bancário.
- `filtrar_usuario(cpf, usuarios)`: Filtra um usuário pelo CPF.
- `criar_conta(agencia, numero_conta, usuarios)`: Cria uma nova conta bancária associada a um usuário existente.
- `listar_contas(contas)`: Lista todas as contas bancárias cadastradas no sistema.

### 2. Função Principal

- `main()`: Função principal que executa o loop do programa e chama as demais funções de acordo com a opção escolhida pelo usuário.
