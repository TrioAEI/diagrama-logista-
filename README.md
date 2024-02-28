# Turma e Trio
Turma: INFO20
Alunos: Carlos Abraão, Erick Marcos e Iziane Sampaio

# Modelo Entidade-Relacionamento para Empresa de Logística

Este é um modelo Entidade-Relacionamento para uma empresa de logística que descreve as entidades e os relacionamentos entre elas.

## Entidades

### Cliente
- ID do cliente
- Nome
- Endereço
- Telefone
- E-mail

### Fornecedor
- ID do fornecedor
- Nome
- Endereço
- Telefone

### Produto
- ID do produto
- Nome do produto
- Descrição
- Peso
- Tamanho
- Preço

### Pedido
- ID do pedido
- Data do pedido
- Status do pedido

### Transportadora
- ID da transportadora
- Nome
- Contato
- Telefone

### Funcionário
- ID do funcionário
- Nome
- Cargo
- Salário

### Armazém
- ID do armazém
- Localização
- Capacidade

## Relacionamentos

1. Cliente faz Pedido (1:N)
2. Fornecedor fornece Produto (1:N)
3. Produto é armazenado no Armazém (M:N)
4. Pedido contém Produto (M:N)
5. Pedido é despachado por Transportadora (1:N)
6. Funcionário trabalha para Transportadora (N:1)
