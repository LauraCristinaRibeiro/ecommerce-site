# ecommerce-site

## 📘 Modelo Conceitual – Narrativas do Negócio

### 🛍️ Narrativa do Produto

- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros).
- Cada produto possui um fornecedor.
- Um ou mais produtos podem compor um pedido.

### 👤 Narrativa do Cliente

- O cliente pode se cadastrar no site com seu CPF ou CNPJ.
- O endereço do cliente irá determinar o valor do frete.
- Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.

### 📦 Narrativa do Pedido

- Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega.
- Um produto ou mais compõem o pedido.
- O pedido pode ser cancelado.

### 🏭 Narrativa do Fornecedor e Estoque

- Cada produto pertence a um fornecedor, responsável por seu fornecimento.
- Um fornecedor pode fornecer mais de um produto.
- O sistema mantém um controle de estoque, identificando a quantidade disponível de cada produto.
- O estoque é atualizado conforme os pedidos são realizados e conforme reposições de produtos.
- O controle de estoque está relacionado diretamente ao produto e pode considerar localizações distintas, caso o sistema evolua para centros de distribuição.
