# Projeto Lógico de um Banco de Dados para Ecommerce


Criar um esquema - Modelo Lógico de Banco de Dados - para um Ecommerce simples 😊  
A partir do modelo conceitual Entidade-Relacionamento, foi desenvolvido o modelo lógico com suas tabelas, colunas, primary key e foreign key, relacionamentos para definir as regras de integridade, estrutura dos dados e normalização.

### Escopo do Ecommerce

**Venda de Produtos**
* Cliente
* Produto
* Pedido
* Estoque
* Fornecedor
* Vendedor Terceiro
* Pagamento
* Entrega
---

Os produtos são vendidos pela plataforma online, contudo, este pode ter vendedores distintos (Terceiros);  
Cada produto possui um Fornecedor;  
Um ou mais produtos podem compor um pedido;  
Cliente pode ser CPF ou CNPj;  
O endereço irá determinar o valor do frete;  
Um cliente pode gerar mais de um pedido;  
O pedido é criado por Cliente e possui informações de compra, endereço, status;  
Um produto ou mais compoem o pedido;  
O pedido pode ser cancelado, entre outras regras que estarão no modelo lógico

### Imagem do Modelo



![Imagem Modelo Lógico](https://github.com/mmota-dark/projeto-conceitual-bd-ecommerce/blob/main/projeto-logico-banco-de-dados-para-e-commerce.png) 

Foi desenvolvido usando o aplicativo **DB Designer**. Para conhecer, acesse a [página](https://www.dbdesigner.net/)

Compartilho também o link direto do meu esquema no db designer:  
[Projeto BD Ecommerce](https://dbdesigner.page.link/kPY5rypqzc6UGx597).  
Poderá ver melhor os relacionamentos de gerar, conter, possuir, ter e a marcação (lado direito) dos tipos de dados, pk, fk, nulos, únicos, entre outros.

---
A modelagem de um ou mais produtos compondo um pedido e a possibilidade de um cliente fazer vários pedidos são reflexos diretos das regras de negócio, e a estrutura de chaves estrangeiras implementada no DB Designer garante que essas relações sejam mantidas de forma consistente.  
Este modelo lógico representa um passo fundamental e bem-sucedido. Ele não apenas formaliza as regras de negócio em uma estrutura de dados, mas também serve como um guia claro e detalhado para a fase de implementação física do banco de dados, garantindo que o sistema final seja confiável, consistente e pronto para crescer, 😉
