# Planejamento de Compras — exportação completa por tamanho

A exportação da aba Estoque por tamanho contém todos os produtos com demanda projetada.

Colunas:
- Loja
- Código
- Descrição
- Tamanho
- Venda LY
- Demanda Projetada
- Estoque atual
- A receber
- Compra sugerida

Regras:
- Produtos de tamanho único são exportados em uma única linha.
- Produtos sem grade identificada são classificados como Único.
- Produtos com vários tamanhos são exportados em uma linha para cada tamanho.
- A soma dos tamanhos preserva os totais de venda, demanda, recebimento e compra do produto.
- Estoque de cada tamanho é lido diretamente da grade dos relatórios finais.
