# AluraStoreBR
Projeto de análise de dados de 4 lojas distintas

## Descrição do Projeto

Este projeto consiste na análise dos dados de vendas de quatro lojas distintas pertencentes ao Sr. João, onde gostaria de obter uma métrica para avaliar a possibilidade de um novo investimento porém considerando o fechamento da loja com menor faturamento.

O objetivo é extrair insights relevantes sobre o desempenho de cada loja, identificar padrões de vendas, entender a satisfação do cliente e analisar a distribuição geográfica das vendas. 

As descobertas servirão como base para recomendações estratégicas para otimizar as operações e aumentar o faturamento.

## Bibliotecas Utilizadas

As seguintes bibliotecas Python foram utilizadas para a análise e visualização dos dados:

*   **pandas:** Para manipulação e análise dos dados em formato de DataFrame.
*   **matplotlib.pyplot:** Para a criação de visualizações estáticas, como gráficos de barras e de dispersão.
*   **numpy:** Para operações numéricas, como a criação de sequências para os eixos dos gráficos.

## Análise e Resultados

### Faturamento Total por Loja

A análise do faturamento total de cada loja revelou as seguintes cifras:

*   **Loja 1:** R$ 1.534.509,12
*   **Loja 2:** R$ 1.488.459,06
*   **Loja 3:** R$ 1.464.025,03
*   **Loja 4:** R$ 1.384.497,58

A Loja 1 apresentou o maior faturamento, enquanto a Loja 4 teve o menor faturamento.

### Vendas por Categoria de Produto

Observamos as categorias de produtos mais e menos vendidas em cada loja:

*   **Loja 1:** Mais vendida: moveis (465 vendas), Menos vendida: utilidades domesticas (171 vendas)
*   **Loja 2:** Mais vendida: moveis (442 vendas), Menos vendida: utilidades domesticas (181 vendas)
*   **Loja 3:** Mais vendida: moveis (499 vendas), Menos vendida: instrumentos musicais (177 vendas)
*   **Loja 4:** Mais vendida: moveis (480 vendas), Menos vendida: instrumentos musicais (170 vendas)

A categoria 'moveis' é consistentemente a mais vendida em todas as lojas.

### Média de Avaliação das Compras

A média de avaliação das compras por loja indica a satisfação geral dos clientes:

*   **Loja 1:** 3.98
*   **Loja 2:** 4.04
*   **Loja 3:** 4.05
*   **Loja 4:** 4.00

Todas as lojas apresentam uma média de avaliação acima de 3.9, indicando um bom nível de satisfação do cliente. A Loja 3 teve a maior média de avaliação.

### Produtos Mais e Menos Vendidos

Identificamos os 3 produtos mais e menos vendidos em cada loja:

*   **Loja 1:** Top 3: {'Micro-ondas': 60, 'TV Led UHD 4K': 60, 'Guarda roupas': 60}, Bottom 3: {'Panela de pressão': 35, 'Headset': 33, 'Celular ABXY': 33}
*   **Loja 2:** Top 3: {'Iniciando em programação': 65, 'Micro-ondas': 62, 'Bateria': 61}, Bottom 3: {'Mesa de jantar': 34, 'Impressora': 34, 'Jogo de tabuleiro': 32}
*   **Loja 3:** Top 3: {'Kit banquetas': 57, 'Mesa de jantar': 56, 'Cama king': 56}, Bottom 3: {'Mochila': 36, 'Micro-ondas': 36, 'Blocos de montar': 35}
*   **Loja 4:** Top 3: {'Cama box': 62, 'Faqueiro': 59, 'Dashboards com Power BI': 56}, Bottom 3: {'Violão': 37, 'Guarda roupas': 34, 'Guitarra': 33}

### Frete Médio por Loja

O custo médio do frete por loja é o seguinte:

*   **Loja 1:** R$ 34,69
*   **Loja 2:** R$ 33,62
*   **Loja 3:** R$ 33,07
*   **Loja 4:** R$ 31,28

A Loja 1 apresenta o maior frete médio, enquanto a Loja 4 tem o menor.

### Distribuição Geográfica de Vendas

A análise da distribuição geográfica das vendas mostra:

*   **Loja 1:** Vendas distribuídas em várias localidades, com alguma concentração no sudeste.
*   **Loja 2:** Vendas espalhadas, com alguns clusters nas regiões sudeste e sul.
*   **Loja 3:** Vendas com uma distribuição geográfica mais ampla, incluindo localidades no nordeste e sul.
*   **Loja 4:** Vendas também geograficamente diversas, com presença no sudeste, sul e nordeste.

## Conclusão e Recomendações

A análise dos dados revela que, embora a Loja 4 tenha o menor faturamento, a diferença no número total de vendas em comparação com as outras lojas é mínima. Isso sugere que a disparidade no faturamento pode estar mais relacionada à localidade e, possivelmente, aos custos de frete associados a essa região.

Considerando que todas as lojas demonstram um bom volume de vendas, uma recomendação inicial seria investigar a possibilidade de otimizar os custos de frete, talvez buscando opções de entrega mais rápidas e eficientes para atrair mais clientes, especialmente na área de atuação da Loja 4.

Fechar a Loja 4 deve ser uma decisão considerada com cautela. Antes de tomar essa medida, é crucial analisar o impacto potencial no alcance geográfico e na base de clientes existentes. Investir em melhorias logísticas e estratégias de marketing direcionadas para a Loja 4 pode ser uma alternativa mais viável para aumentar seu faturamento e equipará-lo às outras lojas. Se, após a análise e implementação de melhorias no frete, a Loja 4 ainda apresentar desempenho significativamente inferior, então a opção de fechamento para realocação de recursos em outras áreas (como a melhoria do frete geral) poderia ser reavaliada.
