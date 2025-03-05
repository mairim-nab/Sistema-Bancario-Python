# Sistema Bancário Básico

Este é um projeto desenvolvido como parte de uma atividade do curso **Python Developer** da **DIO**, em parceria com a **Suzano**. O desafio consistiu em criar um sistema bancário simples que permite ao usuário realizar operações de depósito, saque e consultar o extrato da conta, com algumas limitações específicas para o saque.


## Funcionalidades e Modo de Uso

1. **Depósito**: O usuário informa o valor a ser depositado, e ele será adicionado ao saldo da conta.
2. **Saque**: O usuário pode informar o valor a ser sacado. O sistema verifica se o valor está dentro dos limites (saldo disponível, limite de saque, e número de saques diários).
3. **Extrato**: O usuário pode visualizar todas as transações realizadas, incluindo o saldo atual.
4. **Sair**: O usuário pode sair do sistema a qualquer momento.

## Limitações

- **Limite de Saque Diário**: O usuário pode realizar no máximo 3 saques por dia.
- **Limite de Saque**: Cada saque tem um limite de R$ 500,00.
- **Saldo Insuficiente**: O saque não pode ser maior que o saldo disponível.
