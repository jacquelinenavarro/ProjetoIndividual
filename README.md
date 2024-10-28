# ProjetoIndividual
Turma 3 - Projeto Individual do FAP

# Projeto: Sistema de Gerenciamento de Pedidos

## Curso Back-End com Python / Turma: 03

#### Aluna:  

- [x] Jacqueline Navarro  

#### Professor:  

- [x] André Ribeiro

#### Data prevista para entrega:  

- [x] 30/10/2024 

---

### Contexto do Sistema: Sistema de Gerenciamento de Pedidos

Cenário
Você faz parte de uma equipe de desenvolvimento que está criando um sistema de
gerenciamento de pedidos para uma loja online. A loja oferece uma variedade de
produtos e deseja implementar um sistema que permita aos clientes fazerem
compras de maneira eficiente e segura.
Objetivos do Sistema
O sistema deve permitir o cadastro e a autenticação de usuários (administradores
da loja) e a gestão de clientes e pedidos. Os principais objetivos incluem:

1. Gerenciamento de Usuários : Administradores devem poder criar e gerenciar
suas contas, garantindo a segurança das informações através de autenticação por
login e senha.

2. Cadastro de Clientes : O sistema deve permitir que os clientes se cadastrem,
fornecendo informações básicas como nome e e-mail.

3. Processamento de Pedidos : Os clientes podem fazer pedidos, que serão
registrados com informações sobre a data da compra.

4. Detalhes do Pedido : Cada pedido pode ter múltiplos produtos, e o sistema deve
registrar detalhes como valor e possíveis descontos aplicados a cada produto no
pedido.

5. Catálogo de Produtos : O sistema deve incluir um cadastro de produtos
disponíveis para venda, permitindo que os administradores adicionem novos
produtos à loja.

6. Categoria do Produto.

Entidades do Sistema

1. Usuário
- `usuario_id`: Identificador único do usuário.
- `usuario_login`: Nome de login para autenticação.
- `usuario_senha`: Senha do usuário (armazenada de forma segura).

2. Cliente
- `cliente_id`: Identificador único do cliente.
- `cliente_nome`: Nome do cliente.
- `cliente_email`: Endereço de e-mail do cliente.

3. Pedido
- `pedido_id`: Identificador único do pedido.
- `cliente_id`: Referência ao cliente que fez o pedido.
- `data_compra`: Data em que o pedido foi realizado.

4. DetalhePedido
- `dt_id`: Identificador único do detalhe do pedido.
- `dt_pedido_id`: Referência ao pedido associado.
- `dt_produto_id`: Referência ao produto que faz parte do pedido.
- `dt_valor`: Valor do produto no momento da compra.
- `dt_desconto`: Desconto aplicado ao produto.

5. Produto
- `produto_id`: Identificador único do produto.
- `produto_nome`: Nome do produto.
- `produto_categoria`: Referência a categoria

6. Categoria
- `id_categoria`
- `nome_categoria`

Funcionalidades Esperadas

- Cadastro de usuários com validação de dados.
- Autenticação e gerenciamento de sessões.
- API para cadastro e visualização de clientes.
- Criação e visualização de pedidos, com opção de adicionar produtos ao pedido.
- Registro de detalhes dos pedidos, incluindo valores e descontos.
- Listagem de produtos disponíveis para compra.

Tecnologias Sugeridas

- Python : Para a implementação da lógica do sistema.
- Banco de Dados : Utilização de um banco de dados relacional (como MySQL ou
PostgreSQL) para armazenar as informações.
- Frameworks : Sugestão de usar frameworks como Flask para facilitar o
desenvolvimento.

---

