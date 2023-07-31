# Sistema_Bancario_com_Python.
> Building a Simple Banking System with Python.

## Objetivo Geral 
> Main Goal

- Criar um sistema bancário com as operações: sacar, depositar
e visualizar extrato.

> Create a banking system with operations: withdraw, deposit
and view extract.

# Descrição
> Description

## Operação de depósito
> Deposit Operation

- Deve ser possível depositar valores positivos para a minha
conta bancária. A v1 do projeto trabalha apenas com 1 usuário,
dessa forma não precisamos nos preocupar em identificar qual
é o número da agência e conta bancária. Todos os depósitos
devem ser armazenados em uma variável e exibidos na
operação de extrato.

> It must be possible to deposit positive values ​​for my
Bank account. The v1 of the project only works with 1 user,
that way we don't need to worry about identifying which
is the agency and bank account number. all deposits
must be stored in a variable and displayed in the
extract operation.

## Operação de Saque
> Withdrawal Operation

- O sistema deve permitir realizar 3 saques diários com limite
máximo de R$ 500,00 por saque. Caso o usuário não tenha
saldo em conta, o sistema deve exibir uma mensagem
informando que não será possível sacar o dinheiro por falta de
saldo. Todos os saques devem ser armazenados em uma
variável e exibidos na operação de extrato.

> The system should allow 3 daily withdrawals with a limit
maximum of BRL 500.00 per withdrawal. If the user does not have
account balance, the system should display a message
informing that it will not be possible to withdraw the money due to lack of
balance. All withdrawals must be stored in a
variable and displayed in the extract operation.

## Operação de Deposito
> Deposit Operation

- Essa operação deve listar todos os depósitos e saques
realizados na conta. No fim da listagem deve ser exibido o
saldo atual da conta. Se o extrato estiver em branco, exibir a
mensagem: Não foram realizadas movimentações.
Os valores devem ser exibidos utilizando o formato R$ xxx.xx,
exemplo:
1500.45 = R$ 1500.45

> This operation should list all deposits and withdrawals
performed on the account. At the end of the list, the
current account balance. If the statement is blank, display the
message: No transactions were performed.
Values ​​must be displayed using the format BRL xxx.xx,
example:
1500.45 = BRL 1500.45
