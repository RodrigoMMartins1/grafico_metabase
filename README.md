# Atividade Ponderada
## Ferramenta
O Metabase é uma ferramenta de Business Intelligence (BI) de código aberto que permite a criação de painéis e visualizações de dados de forma intuitiva, podendo realizar consultas sem conhecimento avançado de SQL. Além disso, o processamento dos gráficos são rápidos.

## Dashboard
<img width="906" alt="image" src="https://github.com/RodrigoMMartins1/grafico_metabase/assets/99209230/d1a99fc9-7802-4b53-823a-0010a623b1eb">
<br></br>

## Gráfico Média de Preço por Produto na Bahia
<img width="452" alt="image" src="https://github.com/RodrigoMMartins1/grafico_metabase/assets/99209230/28b224d3-1a42-4d76-8c75-70ef3147a8ea">
<br></br>
- Foi configurado utilizando a tabela cnpj_vendas_bacen final, filtragem por uf, agrupamento por produto e sumarizando por média
<br></br>
- Análise do Gráfico:
Este gráfico representa a média de preços de diferentes produtos na Bahia. Aqui estão os principais pontos:

Título: “Média de Preço por Produto na Bahia”.
Eixos:
Eixo Y: Representa a média de preço em reais (varia de 0 a 550).
Eixo X: Lista vários produtos, como arroz, cerveja, detergente, vinho, entre outros.
Barras:
Cada barra roxa representa um produto específico.
A altura das barras varia, indicando as diferenças nos preços médios dos produtos.
Produtos destacados:
Arroz
Cerveja
Detergente Líquido
Vinho Tinto Seco

<br></br>
## Número de Vinhos por Região
<img width="450" alt="image" src="https://github.com/RodrigoMMartins1/grafico_metabase/assets/99209230/158447e5-0d40-4db9-ac5b-ad3e5b48fb80">
<br></br>
- Foi configurado utilizando a tabela cnpj_vendas_bacen final, filtragem por produto = Vinho, agrupamento por sigla_uf e sumarizando por quantidade
<br></br>
- Análise do Gráfico:
Este gráfico representa o número de vinhos por região no Brasil. Aqui estão os principais pontos:

Título: “Número de Vinhos por Região”.
Eixos:
Eixo Y: Representa a quantidade de vinhos (varia de 0 a 1000).
Eixo X: Lista as siglas dos estados brasileiros, começando com AC (Acre) e terminando com TO (Tocantins).
Barras:
Cada barra roxa representa um estado específico.
A quantidade de vinhos aumenta gradualmente até atingir um pico em SP (São Paulo).
Estado destacado:
São Paulo (SP)

<br></br>
## Produtos mais vendidos em novembro
<img width="452" alt="image" src="https://github.com/RodrigoMMartins1/grafico_metabase/assets/99209230/b7c39a29-18e4-4b03-8cf1-de15f6bebbf9">
<br></br>
- Foi configurado utilizando a tabela cnpj_vendas_bacen final, filtragem por mes = Novembro, agrupamento por produto e sumarizando por quantidade
<br></br>
- Análise do Gráfico:
Este gráfico representa o número de produtos vendidos em Novembro por região no Brasil. Aqui estão os principais pontos:

Título da Tabela: “Produtos mais vendidos em novembro”.
Eixos:
Eixo Y: Representa a quantidade de unidades vendidas (varia de 64 a 1.800).
Eixo X: Lista os nomes dos produtos.
Barras:
Cada barra vermelha representa um produto específico.
A altura das barras indica a quantidade de unidades vendidas para cada produto.
Produtos Destacados:
Vinho (1.800 unidades)
Verniz (1.600 unidades)
Tupperware (1.500 unidades)
Produto Menos Vendido:
Arroz (64 unidades)


