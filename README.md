# Sistema Bancário Básico

Este é um sistema bancário simples, implementado em Python, que permite ao usuário realizar operações de depósito, saque e consultar o extrato da conta. O sistema foi desenvolvido como parte de um desafio, com algumas limitações específicas para o saque.

## Funcionalidades

- **Depositar**: O usuário pode realizar depósitos em sua conta.
- **Sacar**: O usuário pode realizar saques, mas existem limitações:
  - O valor do saque não pode ultrapassar R$ 500,00.
  - O número de saques diários é limitado a 3.
  - O saque não pode exceder o saldo disponível na conta.
- **Extrato**: O usuário pode visualizar o extrato de todas as operações realizadas, incluindo depósitos e saques.

## Como Funciona

1. **Depósito**: O usuário informa o valor a ser depositado, e ele será adicionado ao saldo da conta.
2. **Saque**: O usuário pode informar o valor a ser sacado. O sistema verifica se o valor está dentro dos limites (saldo disponível, limite de saque, e número de saques diários).
3. **Extrato**: O usuário pode visualizar todas as transações realizadas, incluindo o saldo atual.
4. **Sair**: O usuário pode sair do sistema a qualquer momento.

## Limitações

- **Limite de Saque Diário**: O usuário pode realizar no máximo 3 saques por dia.
- **Limite de Saque**: Cada saque tem um limite de R$ 500,00.
- **Saldo Insuficiente**: O saque não pode ser maior que o saldo disponível.
