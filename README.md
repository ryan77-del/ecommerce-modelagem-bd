## 📊 Diagrama do Banco de Dados
![Diagrama](Primeira%20versão%20do%20projeto%20de%20modelagem%20e-commerce/imagens/diagrama-eer.png)




# Projeto de modelagem de banco de dados - E-commerce
O projeto apresenta a modelagem de um banco de dados de um sistema de e-commerce no MySQL Workbench

## Objetivo
Modelar as principais entidades e relacionamentos de vendas online :
- Cliente
- Pedido
- Produto
- Estoque
- Fornecedor
- Terceiros vendedores

## Regras de negócio modeladas:

## Cliente
Cliente pode ser PF ou PJ
Cliente pode fazer vários pedidos
 
## Pedido
Um ou mais produtos compõem um pedido
Pedido possui status
Pedido pode ser cancelado

## Produto
Produto possui fornecedor
Produto pode ser vendido por terceiros

## Logística
Endereço influencia o frete
Entrega possui status e rastreio

## Pagamento
Pagamento pode ter diferentes formas

# Arquivos
- 'diagrama/': Arquivo do MySQL Workbench
- 'imagens/': imagem completa do diagrama

# Ferramentas que eu usei:
- MySQL Workbench
- GitHub



