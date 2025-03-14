# **Sistema Bancário Básico**  

Este é um projeto desenvolvido como parte de uma atividade do curso **Python Developer** da **DIO**, em parceria com a **Suzano**. O desafio consistiu em criar um sistema bancário simples que permite ao usuário realizar operações financeiras básicas, como depósito, saque e consulta de extrato, além de funcionalidades adicionais para cadastro de usuários e contas bancárias.  

## **Funcionalidades e Modo de Uso**  

### **Operações bancárias**  
1. **Depósito**: O usuário informa o valor a ser depositado, e ele será adicionado ao saldo da conta.  
2. **Saque**: O usuário pode informar o valor a ser sacado. O sistema verifica se o valor está dentro dos limites (saldo disponível, limite de saque e número de saques diários).  
3. **Extrato**: O usuário pode visualizar todas as transações realizadas, incluindo o saldo atual.  
4. **Cadastro de Usuário**: Permite registrar novos clientes no sistema, armazenando nome, CPF, data de nascimento e endereço. Cada CPF é único, evitando registros duplicados.  
5. **Cadastro de Conta Bancária**: Cria contas associadas a usuários cadastrados. Cada conta tem um número sequencial e pertence a uma agência fixa.  

### **Regras do sistema**  
- **Limite de Saque Diário**: O usuário pode realizar no máximo 3 saques por dia.  
- **Limite de Saque**: Cada saque tem um limite de R$ 500,00.  
- **Saldo Insuficiente**: O saque não pode ser maior que o saldo disponível.  
- **Cada usuário pode ter mais de uma conta bancária, mas cada conta pertence a apenas um usuário.**  

## **Estrutura do Código**  

Para tornar o sistema mais modular e organizado, as operações foram implementadas como funções específicas:  
- `sacar()`: Função responsável pela operação de saque, garantindo que os limites sejam respeitados.  
- `depositar()`: Permite a adição de saldo à conta do usuário.  
- `exibir_extrato()`: Exibe o histórico de transações realizadas.  
- `criar_usuario()`: Cadastra um novo cliente no sistema.  
- `criar_conta()`: Gera uma nova conta bancária vinculada a um usuário existente.  

Essas funções foram projetadas para receber argumentos de diferentes formas (por posição ou nome), tornando o código mais flexível e organizado.  

## **Tecnologias utilizadas**  
Este projeto foi desenvolvido em **Python** utilizando conceitos de programação funcional e estruturação de dados em listas para armazenamento das informações dos clientes e contas.  

