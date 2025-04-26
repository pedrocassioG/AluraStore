
# Análise de Desempenho de Vendas das Lojas

Este projeto tem como objetivo fornecer ao dono de quatro lojas uma análise detalhada sobre o desempenho de cada loja, para ajudá-lo a identificar qual loja está apresentando os piores resultados e qual loja tem o maior potencial de crescimento. Através dessa análise, o dono poderá tomar decisões informadas sobre onde investir e quais lojas precisam de mais atenção.

## Objetivo

O objetivo principal do projeto é avaliar o desempenho de vendas das quatro lojas, destacando as que estão com resultados mais baixos e sugerindo qual delas pode ser descontinuada ou reestruturada para focar o investimento em outras áreas. As análises incluem:

- **Comparação de faturamento entre as lojas**: Identificar qual loja tem o menor faturamento e o desempenho mais fraco.
- **Análise de vendas por categoria de produto**: Verificar quais categorias de produtos estão gerando mais receita e qual loja está com as menores vendas em certas categorias.
- **Análise de avaliação das lojas**: Verificar a satisfação dos clientes com base nas avaliações médias, o que pode indicar a necessidade de melhorar o serviço ou a qualidade dos produtos.
- **Análise de geolocalização**: Verificar se a localização geográfica das vendas influencia o desempenho das lojas.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Pandas**: Para manipulação e análise dos dados.
- **Matplotlib** e **Seaborn**: Para visualização dos dados.
- **Numpy**: Para operações matemáticas e manipulação de arrays.

## Descrição do Código

### Carregamento dos Dados

Os dados de vendas de cada loja são carregados a partir de arquivos CSV. Cada arquivo contém transações de uma loja específica. O código carrega os dados e adiciona uma coluna de identificação para cada loja.

### Análise de Faturamento por Loja

O código calcula o **faturamento total** de cada loja somando o valor da coluna **'Preço'** de cada transação. Em seguida, é gerado um gráfico de barras para comparar o faturamento total entre as lojas e identificar a que está com o desempenho mais baixo.

### Vendas Mensais por Loja

O gráfico de vendas mensais é gerado para cada loja, mostrando como as vendas evoluem ao longo do tempo. Essa visualização ajuda a identificar variações sazonais ou períodos de baixo desempenho que podem estar impactando a receita da loja.

### Faturamento por Categoria de Produto

Através da soma do faturamento por categoria de produto, é possível ver quais categorias são mais lucrativas para cada loja. Um gráfico de pizza é utilizado para mostrar qual categoria mais contribui para o faturamento total.

### Avaliação Média por Loja

O código calcula a **avaliação média** das lojas com base nas avaliações dos clientes. Esse valor é visualizado em um gráfico de barras, permitindo identificar as lojas com as melhores e piores avaliações. Uma loja com avaliações baixas pode indicar a necessidade de melhorar o atendimento, a qualidade dos produtos ou outros aspectos da experiência do cliente.

### Produto Mais e Menos Vendido

A análise também verifica o **produto mais vendido** e o **menos vendido**, comparando as quantidades. Isso ajuda a entender quais produtos estão sendo mais procurados e quais podem estar subperformando, sugerindo um possível desinvestimento ou substituição.

### Cálculo do Frete Médio por Loja

O código calcula o **frete médio** de cada loja, permitindo uma comparação entre os custos de envio. Lojas com fretes mais caros podem precisar avaliar a logística para reduzir custos e aumentar a competitividade.

### Distribuição Geográfica das Compras

Usando as coordenadas de **latitude** e **longitude**, o código gera gráficos de dispersão para mostrar a **distribuição geográfica das compras**. Isso pode ajudar a identificar regiões com maior ou menor concentração de vendas, fornecendo insights sobre onde as lojas têm melhor ou pior desempenho geograficamente.

## Relatório de Análise

Com base nas análises realizadas, foi possível identificar qual loja apresentou o pior desempenho. O relatório de análise aponta que:

- **Loja 1** teve o maior faturamento, mas possui a pior avaliação média dos clientes e o maior custo de frete. Isso pode indicar que, embora a loja tenha um alto faturamento, a insatisfação dos clientes e o alto custo de frete podem afetar sua sustentabilidade a longo prazo.
- **Loja 4** apresentou o menor faturamento, mas tem a melhor avaliação média e o menor custo de frete, o que indica um bom desempenho em termos de satisfação dos clientes e eficiência logística.

Recomendamos que o dono das lojas considere reestruturar ou até mesmo fechar a **Loja 1**, com base em sua combinação de alto custo, baixa satisfação e baixa avaliação dos clientes.

## Como Executar

1. Certifique-se de ter todas as dependências instaladas.
2. Execute o código em um ambiente Python, como Jupyter Notebook ou Google Colab.
3. Visualize os gráficos gerados nas diferentes seções do código.

## Resultados Esperados

- **Faturamento Total por Loja**: Gráfico de barras comparando o faturamento total entre as lojas, ajudando a identificar a loja com pior desempenho.
- **Vendas Mensais**: Gráficos de linha mostrando a evolução das vendas ao longo dos meses, destacando possíveis períodos de baixo desempenho.
- **Faturamento por Categoria de Produto**: Gráfico de pizza mostrando as categorias mais lucrativas de produtos.
- **Avaliação Média por Loja**: Gráfico de barras comparando as avaliações das lojas e destacando as de menor desempenho.
- **Produto Mais e Menos Vendido**: Gráfico de barras comparando as quantidades dos produtos mais e menos vendidos, ajudando a identificar possíveis produtos a serem descontinuados.
- **Distribuição Geográfica**: Gráfico de dispersão mostrando a localização das compras para entender padrões geográficos de vendas.

## Conclusões Esperadas

Ao final da análise, o dono das lojas poderá identificar qual loja está com o desempenho mais fraco e tomar decisões sobre onde investir ou até mesmo descontinuar a operação de uma loja. Ele também pode ajustar sua estratégia de marketing e logística, com base em fatores como categorias de produtos mais vendidas, avaliações de clientes e localização das vendas.
