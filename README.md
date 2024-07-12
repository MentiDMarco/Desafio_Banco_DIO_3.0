# Sistema Bancário 3.0 - DIO

Esse é um sistema bancário simples implementado em Python, de acordo com as aulas da DIO. O sistema permite criar contas, realizar depósitos, saques e exibir extratos.

## Funcionalidades

- Criar um novo cliente
- Criar uma nova conta para um cliente existente
- Realizar depósitos em contas
- Realizar saques de contas
- Exibir extratos de contas
- Listar todas as contas

## Como usar

1. Ao executar o script, você verá o menu principal com as seguintes opções:
    ```
    =-=-=-=-=-=- MARBANK 3.0 -=-=-=-=-=-=

    [1] Depositar
    [2] Sacar
    [3] Extrato
    [4] Nova conta
    [5] Listar contas
    [6] Novo usuário
    [0] Sair

    Selecione uma opção:
    ```

2. Escolha a opção desejada digitando o número correspondente e siga as instruções fornecidas.

## Estrutura do Código

- `Cliente`: Classe base para clientes, contendo métodos para realizar transações e adicionar contas.
- `PessoaFisica`: Subclasse de `Cliente`, representando clientes pessoas físicas.
- `Conta`: Classe base para contas, contendo métodos para depósito e saque.
- `ContaCorrente`: Subclasse de `Conta`, representando contas correntes com limite de saque e número de saques diários.
- `Historico`: Classe para manter o histórico de transações de uma conta.
- `Transacao`: Classe abstrata para representar transações.
- `Saque` e `Deposito`: Subclasses de `Transacao`, representando saques e depósitos.
- Funções utilitárias: Funções para manipular clientes, contas e transações, além de um menu interativo.

## Créditos

Este projeto foi inspirado pelo curso de Guilherme Carvalho da DIO