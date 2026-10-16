# 📊 Data Science & Martech: Análise de Campanhas de Marketing
📌 Sobre o projeto
Este projeto explora dados de campanhas de marketing com Python para compreender indicadores de desempenho, observar padrões nos resultados e comparar canais de divulgação. A proposta é aplicar técnicas de análise de dados ao contexto de Marketing e Martech, transformando dados em informações que podem apoiar decisões de negócio.
# 🎯 Objetivos
- Explorar a estrutura e a qualidade dos dados das campanhas.
- Identificar os canais de marketing utilizados e sua frequência.
- Calcular e analisar a taxa de cliques (CTR).
- Investigar a distribuição de impressões, custos e receitas.
- Analisar a distribuição das campanhas por estado.
- Calcular o retorno sobre o investimento (ROI).
- Comparar os resultados de ROI dos canais Google Ads e Email.
# 🛠️ Tecnologias e bibliotecas
- Python — linguagem utilizada na análise.
- Pandas — leitura, manipulação e exploração dos dados.
- NumPy — cálculos estatísticos.
- Matplotlib — criação de gráficos.
- Seaborn — visualização e análise da distribuição dos indicadores.
- Jupyter Notebook / Google Colab — ambiente para executar o código e documentar a análise.
# 📂 Arquivos
- DataScienceMartech.ipynb — notebook com as etapas de exploração, cálculos e visualizações.
- campanha.csv — base de dados utilizada pelo notebook. Esse arquivo precisa estar disponível no ambiente de execução.
Importante: o notebook lê a base pelo caminho /content/campanha.csv, normalmente utilizado no Google Colab. Se você executar o projeto em outro ambiente, ajuste o caminho do arquivo no código.

# 🔎 Etapas da análise
1. Exploração e qualidade dos dados
- Visualização inicial dos registros.
- Verificação da quantidade de linhas e colunas e dos tipos de dados.
- Identificação de valores ausentes.
- Levantamento dos canais presentes na base.
2. Análise do CTR
O Click-Through Rate (CTR) representa a proporção de cliques em relação às impressões.
Fórmula utilizada:
CTR = (cliques / impressões) × 100
O notebook calcula o indicador e explora sua distribuição por meio de estatísticas descritivas, mediana, histograma e boxplot. Também calcula a média de CTR por canal.
3. Impressões, custos e receitas
- Análise das impressões por campanha.
- Agrupamento das impressões por identificador de campanha.
- Visualização da distribuição de custos e receitas.
- Contagem e visualização das campanhas por estado, incluindo uma análise separada dos estados diferentes de São Paulo.
4. Análise do ROI
O Return on Investment (ROI) é utilizado para avaliar o retorno em relação ao custo.
Fórmula aplicada no notebook:
ROI = (receita - custo) / custo
O indicador é explorado por meio de gráficos e estatísticas, com comparação entre os canais Google Ads e Email usando média, mediana e desvio padrão.
Observação: no código atual, o ROI é calculado como razão decimal, sem multiplicação por 100. Portanto, para apresentar o resultado em porcentagem, é necessário multiplicar o valor por 100. Além disso, somar os ROIs individuais não equivale necessariamente ao ROI consolidado de todas as campanhas.
# 📈 Principais análises realizadas
- Distribuição e frequência dos canais de marketing.
- Comportamento do CTR e identificação de possíveis valores atípicos.
- Média de impressões por campanha.
- Distribuição dos custos e das receitas.
- Volume de campanhas por estado.
- Distribuição do ROI.
- Comparação do ROI entre Google Ads e Email.
O notebook registra uma interpretação inicial de que o Google Ads apresentou desempenho superior ao Email na comparação realizada. Essa leitura deve ser validada considerando o conjunto de dados, a dispersão dos resultados e possíveis valores atípicos, sem assumir que o mesmo resultado se aplica a outras campanhas.
