# Projeto de modelagem de banco de dados - E-commerce
O projeto apresenta a modelagem de um banco de dados de um sistema de e-commerce no MySQL Workbench

## Objetivo
Modelar as principais entidades e relacionamentos de vendas online :
- Cliente
- Pedido
- Produto
- Estoque
- Fornecedor
- Estoque
- Terceiros vendedores

## Regras de negócio modeladas:
- Produtos podem ter vendedores(Terceiros) distintos
- Cada produto possui um ou mais fornecedores
- Um ou mais pedidos podem compor um pedido
- Cliente pode se cadastrar com CPF ou CNPJ
- Endereço determina valor do frete
- Pedido tem tempo de carência para devolução
- Pode ser cadastrado mais de uma forma de pagamento
- Entrega deve possuir status e código de rastreio

# Arquivos
- ![Diagrama EER](imagens/diagrama-eer.png': Arquivo do MySQL Workbench
- 'imagens do diagrama/': imagem completa do diagrama

# Ferramentas que eu usei:
- MySQL Workbench
- GitHub
