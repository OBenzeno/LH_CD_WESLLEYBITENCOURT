# LH_CD_WESLLEYBITENCOURT
LIGHTHOUSE | Terceira etapa do processo seletivo - Desafio técnico

------

# INTRODUÇÃO
Inicialmente a ideia era de se usar um modelo de regressão linear simples para prever preços futuros. Porém, como ainda existem outliers que passaram a filtragem, é necessário o uso de um modelo mais robusto que não se deixe ser afetado por outliers. Como não tenho tanta experiência com o uso de machine learning, fiz um modelo de regressão random forest por ser mais simples. Esse modelo é mais robusto que o modelo de regressão linear simples, porém ele ainda é falho a outliers. Portanto os resultados podem não ser os mais confiáveis, sendo a necessidade de se utiliar um modelo com maior robustez a outliers. Ao fim do arquivo possui um modelo de regressão linear simples para fins comparativos, a fim de confirmar a afirmação quanto a robustez, porém a variação de resultados não é considerada tão significativa, confirmando a necessidade de um tratamento melhor dos dados.

------

# LEGENDA
# A Pasta Notebooks é Subdividida em:
1. Data - Dataset original e Dataset filtrado para testes
2. Models - Notebook com Modelo preditivo
3. Reports - Notebook com o Relatório da Análise Exploratória de Dados (EDA)

------

# Arquivos Principais
1. LH_CD_WESLLEYBITENCOURT.pkl - Modelo de Machine Learning Treinado
2. LH_CD_WESLLEYBITENCOURT_RELATÓRIO.ipynb - Relatório
3. LH_CD_WESLLEYBITENCOURT_MODELO_RF.ipynb - Código do Modelo

OBS.: O Arquivo relatório possui uma cópia do modelo de previsão, apenas para fins de teste durante a realização do Desafio.

------

# TESTES REALIZADOS NO MODELO
- MAE (Mean Absolute Error) - Erro Absoluto Médio
- MSE (Mean Squared Error) - Erro Quadrático Médio
- R² (Coeficiente de Determinação)

------

# PASSO A PASSO
# Para execução do arquivo .pkl:
1. verifique as dependências
2. instalação:
- Utilize o Python global do sistema - Não recomendado
ou
- Crie um ambiente virtual - Opcional, mas altamente recomendado
ou
- Crie um Container - Evita os problemas relacionados ao Python global
3. importar as bibliotecas utilizadas no modelo
4. importar pickle ou joblib - carregar o arquivo .pkl
5. teste o modelo

------

# Possíveis erros
- ModuleNotFoundError - Ambiente não possui as bibliotecas necessárias
- AttributeError - Incompatibilidade de versão
- PickleError - Arquivo corrompido

------
