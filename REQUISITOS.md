LIGHTHOUSE | Terceira etapa do processo seletivo - Desafio técnico

------

# REQUISITOS PARA EXECUÇÃO DO ARQUIVO "LH_CD_WESLLEYBITENCOURT_RELATÓRIO.ipynb"

------

# VISUALIZAÇÃO
- Python 3.12.5
- Jupyter Notebook 7.0.8 <br>
ou
- Jupyter Lab 4.0.11 <br>
ou 
- Google Colab <br>

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
1. import pickle ou joblib - Salvar o modelo no formato .pkl
2. import os - Confirmar a presença do arquivo no diretório
3. from google.colab import files - Download do Arquivo

------
