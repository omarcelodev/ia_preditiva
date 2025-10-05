# 🔮 Value Prediction with LSTM

This is an academic project focused on developing a predictive model using LSTM (Long Short-Term Memory) neural networks to forecast corn prices based on time series data. The main goal is to apply artificial intelligence concepts to a real-world forecasting problem.

---

## 🧠 Objective

Build an LSTM model capable of predicting future values from historical data, using preprocessing, normalization, and training techniques with Keras/TensorFlow.

---

## 💻 Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## 📁 Project Structure

├── 📁 dataset/  

├── 📄 LSTMilho.ipynb  

└── 📄 README.md  


---

## 📋 Project Steps

- Data collection  
- Exploratory data analysis  
- Train-test split  
- Data normalization  
- LSTM model building  
- Model training  
- Loss evaluation  
- Predictions evaluation on test data  
- Model performance assessment  
- Future data prediction  
- Evaluation of future predictions  

---

## 📊 Data Used

Data was collected from [CEPEA/ESALQ](https://www.cepea.org.br/br/indicador/milho.aspx)

---

## 📋 Results

### Loss Graph
![image](https://github.com/user-attachments/assets/fb8f8784-68b7-4477-a542-95da3ee2d975)

- **RMSE:** 1.0793  
  (Root Mean Squared Error: measures the square root of the average squared errors)  
- **MAE:** 0.7790  
  (Mean Absolute Error: measures the average absolute errors)

### Predicted vs Actual Values
![image](https://github.com/user-attachments/assets/38e03994-ef57-4841-a374-995c047f4acf)

- The orange line (predicted values) closely follows the blue line (actual values), with minor fluctuations during the pandemic period.

### Final Comparison
![image](https://github.com/user-attachments/assets/b9b4ca50-27e2-4849-b4e4-3ac886657d0d)

### Forecast Graph
![image](https://github.com/user-attachments/assets/e1a4c031-eeec-46fa-9dba-619561f3aea3)

- Predictions were made for 10 days ahead starting **12/05/2025**.

### Predicted Values
![Predicted Values](https://github.com/user-attachments/assets/b324d600-9b8f-4682-a717-688c703bf332)

- The model achieved low error rates even without considering external factors like weather or USD exchange rate.

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

---

## ▶️ How to Run

1. Open the `📄 LSTMilho.ipynb` file in [Google Colab](https://colab.research.google.com).  
2. Go to **"Runtime → Run all"**, or press **Ctrl + F9**.

> ⚠️ Note: Predicted values may vary due to the absence of external factors in the model.

