# carrinho_correcao

1. **querySelector():** Este método é utilizado para escolher um elemento específico com base no seu seletor CSS. Neste projeto, é utilizado para selecionar o elemento .curso e também os elementos .carrinho_compra, .carrinho_total e .btn-remove.

2. **querySelectorAll():** Este método é usado para selecionar todos os elementos que correspondem a um seletor CSS específico. No contexto deste projeto, é utilizado para selecionar todos os elementos .btn-add.

3. **addEventListener():** Esta função é usada para associar um ouvinte de eventos a um elemento. No projeto, é utilizada para adicionar um ouvinte de eventos de clique aos elementos .btn-add e .btn-remove.

4. **Função renderizaProdutos():** Esta função é responsável por exibir uma lista de produtos na página. A função utiliza um laço de repetição for para percorrer o array de produtos e criar um elemento .curso para cada produto.

5. **Função criaProduto():** Esta função é utilizada para criar a representação de um único produto na página. A função recebe como argumento um objeto de produto e retorna um elemento .curso com informações sobre o produto.

6. **Função renderizaCarrinho():** Esta função é responsável por mostrar uma lista de itens no carrinho na página. A função utiliza um laço de repetição for para percorrer o objeto carrinhoItens e criar um elemento .carrinho_compra para cada item do carrinho.

7. **Função criaItemCarrinho():** Esta função é utilizada para criar a representação de um único item no carrinho na página. Ela recebe um objeto item de carrinho como argumento e retorna um elemento .carrinho_compra.

8. **Laço de repetição - For:** Este tipo de estrutura é utilizada para iterar uma coleção de elementos. No contexto deste projeto, é usado para percorrer o array de produtos e criar uma lista de itens no carrinho para cada produto.
