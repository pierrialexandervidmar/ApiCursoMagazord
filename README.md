# API de Produtos e Categorias (Curso Magaozord)

## Descrição
Esta API fornece endpoints para gerenciar produtos e categorias.
Finalidade: Ministrado no curso de Conceitos de HTTP e Webservices ministrado por Pierri Alexander Vidmar em 03/2024

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



