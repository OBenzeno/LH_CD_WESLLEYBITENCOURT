# LH_CD_WESLLEYBITENCOURT
LIGHTHOUSE | Terceira etapa do processo seletivo - Desafio técnico

------

# INTRODUÇÃO
Inicialmente a ideia era de se usar um modelo de regressão linear simples para prever preços futuros. Porém, como ainda existem outliers que passaram a filtragem, é necessário o uso de um modelo mais robusto que não se deixe ser afetado por outliers. Como não tenho tanta experiência com o uso de machine learning, fiz um modelo de regressão random forest por ser mais simples. Esse modelo é mais robusto que o modelo de regressão linear simples, porém ele ainda é falho a outliers. Portanto os resultados podem não ser os mais confiáveis, sendo a necessidade de se utiliar um modelo com maior robustez a outliers. Ao fim do arquivo possui um modelo de regressão linear simples para fins comparativos, a fim de confirmar a afirmação quanto a robustez, porém a variação de resultados não é considerada tão significativa, confirmando a necessidade de um tratamento melhor dos dados.

------

# LEGENDA 
1. LH_CD_WESLLEYBITENCOURT_RELATÓRIO - Relatório
2. LH_CD_WESLLEYBITENCOURT_RF - Modelo de Machine Learning para teste

# OBS.: O Arquivo relatório possui uma cópia dos modelos de previsão, apenas para fins de teste durante a realização do Desafio.
# OBS.2: Para avaliar o relatório é necessário executar as células de código em sequência, haja vista que foi feito utilizando o Google Colab.

------

# PASSO A PASSO
1. Para executar o arquivo com o modelo é necessário o uso de um notebook, seja Jupypter Notebook, Jupyter Lab ou Google Colab. 
2. Após aberto o arquivo, é necessário executar a célula com as bibliotecas que serão importadas.
3. Em seguida, deve ser executada a célula para importar o DataFrame de testes.
4. Após a importação das bibliotecas e do DataFrame, é necessário executar as duas células seguintes para realizar o treinamento do modelo e exibir os resultados de avaliação, como MAE, MSE e R².
5. Feito isso, é só executar a célula de código indicada como "Teste 1", a qual vai importar os dados listados no desafio como um novo DataFrame assim realizando a previsão.
6. Após executado o primeiro modelo, se necessário, realizar o "Teste 2" com o segundo modelo, apenas para fins comparativos.

------

