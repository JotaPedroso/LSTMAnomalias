
# 🔍 Detecção de Anomalias com LSTM

Projeto de detecção de anomalias em séries temporais de vendas utilizando uma rede neural LSTM (Long Short-Term Memory) profunda. O modelo é treinado com dados históricos normais e, ao ser exposto a dados com anomalias simuladas, gera previsões divergentes, revelando os pontos anômalos pela discrepância entre o valor previsto e o valor real.






# 📌 Descrição do Problema

Em séries temporais, anomalias são pontos que fogem do comportamento esperado — picos, quedas abruptas ou padrões incomuns. Este projeto simula artificialmente um período anômalo nos dados de vendas e avalia se o modelo LSTM é capaz de identificá-lo através do erro de previsão (MSE).



# 🛠️ Tecnologias Utilizadas
Python 3

TensorFlow / Keras — construção e treino da LSTM

Scikit-learn — normalização (MinMaxScaler) e métricas (MSE)

Pandas / NumPy — manipulação dos dados

Matplotlib — visualização das séries e previsões

