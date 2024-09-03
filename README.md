# Sistema Bancário Orientado a Objetos

Este projeto é uma atualização de um sistema bancário simples, que agora armazena dados de clientes e contas bancárias usando a programação orientada a objetos (POO) em Python. O código segue um modelo de classes UML, permitindo uma estrutura mais organizada, modular e fácil de manter.

## Desafio

O objetivo deste desafio foi refatorar a implementação do sistema bancário para utilizar objetos em vez de dicionários, seguindo os princípios da programação orientada a objetos. O sistema agora gerencia clientes e contas bancárias através de classes, representando de forma mais natural e organizada as entidades envolvidas.

### Modelo UML Simplificado

- **Classe `Cliente`**: Representa um cliente do banco.
  - **Atributos**: `nome`, `cpf`, `contas`
  - **Métodos**: `adicionar_conta(conta)`

- **Classe `ContaBancaria`**: Representa uma conta bancária.
  - **Atributos**: `numero`, `saldo`, `transacoes`
  - **Métodos**: `depositar(valor)`, `sacar(valor)`, `extrato()`

- **Classe `Banco`**: Representa o banco que gerencia clientes e contas.
  - **Atributos**: `clientes`, `contas`
  - **Métodos**: `adicionar_cliente(cliente)`, `adicionar_conta(conta)`, `buscar_cliente(cpf)`, `buscar_conta(numero)`



