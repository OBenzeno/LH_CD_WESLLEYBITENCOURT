LIGHTHOUSE | Terceira etapa do processo seletivo - Desafio técnico

------

# REQUISITOS PARA EXECUÇÃO DO ARQUIVO "LH_CD_WESLLEYBITENCOURT_RELATÓRIO.ipynb"

------

# VISUALIZAÇÃO
- Python 3.12.5
- Jupyter Notebook 7.0.8
ou
- Jupyter Lab 4.0.11
ou 
- Google Colab

------

# BIBLIOTECAS

# Para o relatório:
1. numpy - Operações de Dados e Arrays
2. pandas - Leitura de DataFrames
3. matplotlib.pyplot - Graficos e Visualização
4. seaborn - Graficos e Visualização

------

# Para os modelos preditivos:
1. scikit-learn - normalização, padronização e tratamento

------

# Para execução do código do modelo preditivo random forest (RF):
1. import numpy as np
2. import pandas as pd
3. from sklearn.model_selection import train_test_split
4. from sklearn.ensemble import RandomForestRegressor
5. from sklearn.metrics import mean_absolute_error
6. from sklearn.metrics import mean_squared_error, r2_score
7. from sklearn.preprocessing import StandardScaler

------

# Para execução do código do modelo preditivo regressão linear simples (RL):
1. import numpy as np
2. import pandas as pd
3. from sklearn.model_selection import train_test_split
4. from sklearn.linear_model import LinearRegression
5. from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
6. from sklearn.preprocessing import StandardScaler

------

# Para importar o modelo no formato .pkl:
1. import pickle - 
2. import os - Confirmar a presença do arquivo no diretório
3. from google.colab import files - Download do Arquivo

------

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
