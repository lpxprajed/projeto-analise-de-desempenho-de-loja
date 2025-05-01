# Análise de Desempenho de Lojas - Projeto de Análise de Dados Alura Store

## 📍 Introdução ao Projeto
Este projeto tem como objetivo realizar uma análise detalhada das lojas do Sr. João. A partir de dados simulados de vendas, o projeto busca entender o desempenho de quatro lojas da rede Alura Store, com o objetivo de recomendar qual loja deve ser vendida para ter um capital para investir em um novo negócio.

## 🎯 Objetivos da Análise
O objetivo da análise é identificar qual loja tem o pior desempenho com base nas seguintes métricas:
- Faturamento total
- Vendas por categoria de produto
- Média das avaliações dos clientes
- Produtos mais e menos vendidos
- Custo médio de frete

## 🧠 Metodologia
A análise foi conduzida utilizando a linguagem Python, com as bibliotecas Pandas e Matplotlib. O processo seguiu as etapas abaixo:

1. **Importação dos Dados**: Utilizamos pandas para carregar os dados de vendas simuladas.
2. **Exploração e Análise**: Realizamos a análise dos dados, calculando os principas valores como faturamento, vendas por categoria, e frete médio.
3. **Visualização**: Utilizamos gráficos para destacar as métricas mais importantes.

## 🔧 Ferramentas Utilizadas
- Language **Python 3.x**
- **Jupyter Notebook**
- **Pandas**: Manipulação e análise de dados
- **Matplotlib**: Visualizações de dados

## 📊 Visualizações e Insights
### 1. Faturamento Total por Loja
Analisamos o faturamento de cada loja, destacando os valores totais.

### 2. Vendas por Categoria
Exibimos a distribuição de vendas e o faturamento por categoria de produtos de cada loja.

### 3. Média de Avaliações dos Clientes
Calculamos a média de avaliações dos clientes para cada loja, destacando os feedbacks dos consumidores.

### 4. Produtos Mais e Menos Vendidos
Identificamos os produtos mais e menos vendidos em cada loja, oferecendo uma visão detalhada do portfólio de produtos.

### 5. Custo Médio de Frete
Analisamos o custo médio de frete por loja. proporcionando uma visão do impacto logístico nas vendas.

## 📁 Estrutura do Projeto
O repositório contém os seguintes arquivos:
- `Análise_Desempenho_Lojas.ipynb`: Notebook com o código da análise, cálculos, tabelas e gráficos.
- `README.md`: Este documento, com detalhes sobre o projeto e instruções para execução.

## 📝 Instruções para Executar o Projeto
### Pré-requisitos
- Python 3.8+
- Jupyter Notebook
- Bibliotecas: pandas e matplotlib
- Ou apenas baixe e execute no [Google Colab](https://colab.google/)

### Passos
1. Clone o repositório:
   ```bash
   gh repo clone lpxprajed/analisando-dados-de-lojas
   cd analisando-dados-de-lojas
   ```
2. Crie e ative o ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scriptsctivate     # Windows
   ```
3. Instale as dependências:
   ```bash
   pip install pandas matplotlib jupyter
   ```
4. Execute o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Abra e execute o notebook `Análise_Desempenho_Lojas.ipynb`.

## 📊 Uma analise geral

|index|Loja|Faturamento|% do Faturamento|Produtos Vendidos|Média Avaliação|Qtd\. Avaliações|Frete Médio \(R$\)|
|---|---|---|---|---|---|---|---|
|0|Loja 1|R$ 1,534,509\.12|26\.13%|2359|3\.98|2359|34\.69|
|1|Loja 2|R$ 1,488,459\.06|25\.35%|2359|4\.04|2359|33\.62|
|2|Loja 3|R$ 1,464,025\.03|24\.93%|2359|4\.05|2359|33\.07|
|3|Loja 4|R$ 1,384,497\.58|23\.58%|2358|4|2358|31\.28|
|4|Total|R$ 5,871,490\.79|100\.00%|9435|-|-|-|

## 🔎 Recomendações Finais
A melhor escolha para ser vendida é a Loja 4. Isso se baseia em alguns fatores importantes analisados: ela teve o menor faturamento entre as quatro lojas, representando 23,58% do total, com uma diferença de R$ 150.011,54 em relação à loja que mais faturou. Mesmo tendo um número de produtos vendidos parecido com o da loja líder em faturamento, a Loja 4 não converteu essas vendas em receita da mesma forma, o que mostra um desempenho financeiro abaixo das demais.

Além disso, a Loja 4 teve o menor valor de frete,o que seria algo positivo mas não converteu em receita, e ficou com a segunda pior avaliação, o que também pode afetar negativamente as vendas e a confiança dos clientes.

Por esses motivos, vender a Loja 4 parece ser a decisão mais adequada no momento.

## 🚀 Autor
Desenvolvido por [Miguel Lopes](https://www.linkedin.com/in/miguel-lopes-ab8a97268/)

## 📚 Agradecimentos
Agradecemos à Oracle e à Alura pela oportunidade de aprendizado e desenvolvimento deste projeto.
