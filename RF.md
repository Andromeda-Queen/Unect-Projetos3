# 1. Requisitos Funcionais

<p align="justify">A <i>Tabela 1</i> a seguir contém os Requisitos Funcionais (RF) elicitados utizando a técnica de Brainstorm.</p>

| ID   |                                 Requisito                                 | Prioridade | Requisitos Relacionados |
| :--: | :-----------------------------------------------------------------------: | :--------: | :---------: |
| RF01 | O sistema deve permitir o cadastro de produtos com nome, código de barras, SKU, descrição e imagens. |  Alta  | RF02, RF06  |
| RF02 | O usuário pode definir categorias e variantes para produtos (ex: cor, tamanho, peso).|  Média  | RF01   |
| RF03 | O sistema deve registrar todas as entradas e saídas de produtos no estoque.  | Alta | RF04, RF07, RF08 |
| RF04 | O sistema deve permitir a transferência de produtos entre armazéns ou locais de estoque.  |  Alta  |  RF03, RF11 |
| RF05 | O sistema deve permitir o rastreamento de produtos por lote e número de série.  | Alta  | RF03, RF09 |
| RF06 | O usuário pode definir níveis mínimos e máximos de estoque e receber alertas de reabastecimento. | Média | RF01, RF07 |
| RF07 | O sistema deve atualizar o estoque automaticamente com o recebimento de pedidos de compra. | Alta  |  RF03, RF06, RF08  |
| RF08 | O sistema deve reduzir a quantidade em estoque automaticamente quando um pedido de venda é confirmado.  |  Alta  | RF03, RF07  |
| RF9  | O sistema deve permitir o monitoramento da data de validade de produtos perecíveis. |  Média  | RF05   |
| RF10 | O sistema deve registrar um histórico detalhado de todas as movimentações de estoque. | Alta | RF03, RF05, RF12  |
| RF11 | O sistema deve permitir o gerenciamento de múltiplos armazéns e depósitos. | Média | RF04 |
| RF12 | O usuário pode gerar relatórios de movimentação, produtos em estoque e previsão de demanda. | Média | RF10 |
| RF13 | O sistema deve permitir a leitura e impressão de códigos de barras para produtos. | Alta | - |
| RF14 | O administrador pode definir permissões para diferentes perfis de usuários. | Alta | - |
| RF15 | O sistema deve permitir a importação e exportação de dados de estoque em formatos como CSV e Excel. | Média | - |



<div style="text-align: center">
<p>Tabela 1: Requisitos Funcionais</p>
</div>

# 2. Referências


<a href="../README.md">VOLTAR INÍCIO</a>
