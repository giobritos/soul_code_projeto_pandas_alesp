# Projeto de ETL Alesp

## Descrição
O projeto de ETL Alesp é uma análise de dados utilizando a biblioteca Pandas e a base de dados pública da Assembleia Legislativa do Estado de São Paulo (Alesp). O projeto foi realizado durante o Bootcamp de Engenharia de Dados da SoulCode Academy.

## Instalação de bibliotecas
Antes de executar o código, é necessário instalar a biblioteca Pandera. Para isso, utilize o seguinte comando:
```bash
pip install pandera
```

## Detalhamento das atividades realizadas
- Importação das bibliotecas Pandas, Pandera e NumPy.
- Extração da base de dados da Alesp disponível em formato CSV de um repositório público.
- Criação de cópias de backup dos DataFrames para evitar perda de dados durante o tratamento.
- Pré-análise dos dados, verificando os tipos de dados, valores ausentes e estatísticas básicas dos valores numéricos.
- Tratamento inicial dos dados, incluindo mudanças nos tipos de dados, renomeação de colunas e limpeza de valores inconsistentes.
- Busca por mais inconsistências específicas nos dados.
- Criação de filtros para limpeza de dados em categorias específicas.
- Criação de um novo DataFrame resultado do merge entre os DataFrames de despesas e cadastro da Alesp.
- Utilização de operações de agrupamento (GROUP BY) nos dados para analisar quantidades de entradas em determinadas categorias.
- Criação de gráficos de barras, linhas e pizza para visualizar os resultados das análises usando a biblioteca Matplotlib.
- Por fim, o DataFrame final com os dados tratados é salvo em um arquivo CSV chamado 'alesp_correto.csv'.


## Autor
O projeto foi desenvolvido por [Giovana de Brito Silva](https://github.com/giobritos).
