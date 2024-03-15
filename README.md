# API de Produtos e Categorias (Curso Magazord)

## Descrição
Esta API fornece endpoints para gerenciar produtos e categorias.
Finalidade: Ministrado no curso de Conceitos de HTTP e Webservices ministrado por Pierri Alexander Vidmar em 03/2024 para a Magazord Digital Commerce

Gist com script: https://gist.github.com/pierrialexandervidmar/ee6af63a7d9ffd3766c44dc8ee8d88b6

## Recursos

- [Listar Categorias](#listar-categorias)
- [Criar Categoria](#criar-categoria)
- [Detalhes da Categoria](#detalhes-da-categoria)
- [Atualizar Categoria](#atualizar-categoria)
- [Excluir Categoria](#excluir-categoria)
- [Listar Produtos](#listar-produtos)
- [Criar Produto](#criar-produto)
- [Detalhes do Produto](#detalhes-do-produto)
- [Atualizar Produto](#atualizar-produto)
- [Excluir Produto](#excluir-produto)



### Listar Categorias
GET /api/categories

Retorna uma lista de todas as categorias.



### Criar Categoria
POST /api/categories

Cria uma nova categoria.

Payload da requisição:

```json
{
    "name": "Nome da Categoria"
}
```



### Detalhes da Categoria
GET /api/categories/{id}

Retorna os detalhes de uma categoria específica.



### Atualizar Categoria
PUT /api/categories/{id}

Atualiza uma categoria existente.

Payload da requisição:

```json
{
    "name": "Novo Nome da Categoria"
}
```


### Excluir Categoria
DELETE /api/categories/{id}

Exclui uma categoria existente.



### Listar Produtos
GET /api/products

Retorna uma lista de todos os produtos com detalhes de categoria.


### Criar Produto
POST /api/products

Cria um novo produto.

Payload da requisição:

```json
{
    "name": "Nome do Produto",
    "description": "Descrição do Produto",
    "price": 99.99,
    "category_id": 1
}
```

### Detalhes do Produto
GET /api/products/{id}

Retorna os detalhes de um produto específico.


### Atualizar Produto
PUT /api/products/{id}

Atualiza um produto existente.

Payload da requisição:

```json
{
    "name": "Novo Nome do Produto",
    "description": "Nova Descrição do Produto",
    "price": 129.99,
    "category_id": 2
}
```

### Excluir Produto
DELETE /api/products/{id}

Exclui um produto existente.

### Autor
Pierri Alexander Vidmar
