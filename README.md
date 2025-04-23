# Projeto_Sistema_Bancario.py
Projeto de um sistema bancário simples utilizando python 3.
O projeto consiste em criar um sistema bancário simples com 3 operações, Depósito, Saque e Extrato.

As condicoes do desafio eram que: 

Na operação de depósito deve ser possível depositar valores positivos, essa Versão 1 trabalha apenas com um usuario,
portanto, ainda não tem um sistema de crição de conta e agencia.
Cada depósito deve ser armazenado em uma variável na operação extrato.

Na operação saque deve ser possível realizar 3 saques diarios com limite máximo de R$ 500,00 por saque. Caso
o usuário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não é possivel sacar o 
dinheiro por falta de saldo. Todos os saques devem ser armazenados em uma variável e exibidos na operacao de extrato.

Na operação de extrato deve listar todos os depósitos e saques realizados na conta. No fim da listagem deve ser exibido
o saldo atual da conta.
Os valores devem ser exibidos utilizando o formato R$ xxx.xx, por exemplo: R$ 1499.99

Na versão 2 foi adicionado tres novas funções: 

Operação de criar usuário, onde o programa deve armazenar os usuários em uma lista, cada usuário é composto por: nome, data de nascimento, cpf e endereço. 
o endereço é uma string com o formato: (logradouro, nro - bairro - cidade/sigla estado). Deve ser armazenado somente os números do CPF e 
não podemos cadastrar 2 usuários com o mesmo CPF.

Operação de criar conta, o programa deve armazenar contas em uma lista, uma conta é composta por: agencia, número da conta e usuário. 
O numero da conta é sequencial, iniciando em 1. O número da agencia é fixo "0001". O usuário pode ter mais de uma conta, mas uma conta
pertence somente a um usuário

Operação de listar contas, o programa lista todas as contas existentes semelhante a operação de extrato
