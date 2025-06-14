# 🔮Previsão de Valores com LSTM
Este é um projeto acadêmico que visa desenvolver um modelo preditivo utilizando redes neurais LSTM (Long Short-Term Memory) para prever valores do milho com base em séries temporais. O foco principal é aplicar conceitos de inteligência artificial em um problema real de previsão.

## 🧠Objetivo 

Criar um modelo LSTM capaz de prever valores futuros a partir de dados históricos, utilizando técnicas de pré-processamento, normalização e treinamento com Keras/TensorFlow.

## 💻Tecnologias Utilizadas

- Python3
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- TensorFlow / Keras

## 📁Estrutura do projeto

├── 📁 dataset/  

├── 📄 LSTMilho.ipynb  

└── 📄 README.md  


## 📋Etapas do projeto

- Coleta de dados
- Análise exploratória
- Divisão do dataset em treino e teste
- Normalização dos dados
- Construção do modelo LSTM
- Treinamento do Modelo
- Avaliação de perda
- Avaliação de previsões com dados testes
- Avaliação da performance do modelo
- Prevendo dados futuros
- Avaliação da previsão de dados futuros
  
## 📊Dados Utilizados
Os dados foram coletados do site [CEPEA/ESAQL](https://www.cepea.org.br/br/indicador/milho.aspx)

## 📋Resultados obtidos
### Gráfico de perda
![image](https://github.com/user-attachments/assets/fb8f8784-68b7-4477-a542-95da3ee2d975)
- **RMSE:** 1.0793  
  (Erro Quadrático Médio: mede a raiz da média dos quadrados dos erros).
- **MAE:** 0.7790  
  (Erro Absoluto Médio: mede a média dos erros absolutos).

### Comparação de valores
![image](https://github.com/user-attachments/assets/38e03994-ef57-4841-a374-995c047f4acf)
- A linha laranja (valores previstos) acompanha bem a linha azul (valores reais), com leve oscilação durante o período da pandemia.

### Comparação de valores final
![image](https://github.com/user-attachments/assets/b9b4ca50-27e2-4849-b4e4-3ac886657d0d)

### Gráfico de previsões
![image](https://github.com/user-attachments/assets/e1a4c031-eeec-46fa-9dba-619561f3aea3)
- Foram feitas previsões para 10 dias no futuro a partir de **12/05/2025**.

### Valores previstos
![Valores previstos](https://github.com/user-attachments/assets/b324d600-9b8f-4682-a717-688c703bf332)
- O modelo apresentou baixa taxa de erro, mesmo sem considerar fatores externos como clima ou câmbio do dólar.

## 📝 Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

## ▶️ Como executar

1. Abra o arquivo `📄 LSTMilho.ipynb` no [Google Colab](https://colab.research.google.com).
2. Vá em **"Ambiente de execução" → "Executar tudo"**, ou pressione **Ctrl + F9**.

> ⚠️ Observação: Os valores previstos podem apresentar variações devido à ausência de fatores externos no modelo.


