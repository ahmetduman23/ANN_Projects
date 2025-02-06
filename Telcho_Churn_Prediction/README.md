# 📡 Telco Customer Churn Prediction with ANN

## 🚀 Project Overview
Predicting customer churn is crucial for telecom companies to retain valuable customers. This project leverages an **Artificial Neural Network (ANN)** to analyze customer data and predict churn behavior effectively. By identifying at-risk customers, businesses can take proactive measures to improve retention strategies.

---

## 📊 Dataset Overview
### **Context**
> "Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." - [IBM Sample Data Sets]

### **Dataset Description**
Each row represents an individual customer, with multiple attributes related to:
- **Customer Churn**: Whether a customer left within the last month (`Churn` column).
- **Services**: Subscribed services, including phone, internet, streaming, and tech support.
- **Account Information**: Contract type, billing method, monthly & total charges.
- **Demographics**: Gender, age range, partner, and dependents.

📌 **Dataset Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 🛠 Installation
To run this project, install the required dependencies:

```bash
pip install -r requirements.txt


- TensorFlow==2.18.0
- Keras
- Pandas
- Numpy
- Matplotlib
- Scikit-learn
- joblib
You can install the dependencies using the following:
```
---

## 🔄 Data Preprocessing
✅ **Handling Missing Values**: Missing values were replaced with the mode of the respective columns.

✅ **Feature Scaling**: MinMaxScaler was applied to normalize features, improving model performance.

✅ **Categorical Encoding**: Categorical variables were converted into numerical format using one-hot encoding.

## 🧠 Model Architecture
The ANN model consists of the following layers:

🔹 **Input Layer**: 10 input nodes corresponding to dataset features.
🔸 **Hidden Layers**: Two fully connected layers with **64 neurons each**, using **ReLU activation**.
🔻 **Output Layer**: A single neuron with **sigmoid activation** to predict churn probability.

## ⚙️ Model Training
The model was trained using the following configurations:

- **Optimizer**: Adam 🟢
- **Loss Function**: Binary Crossentropy ⚖️
- **Metrics**: Accuracy, Precision, Recall 📈
- **Epochs**: 100 ⏳
- **Batch Size**: 32 🔄

## 📈 Results
| **Metric**   | **Value** |
|-------------|-----------|
| 🔹 **Accuracy**  | 85%       |
| 🔹 **AUC**       | 91%       |
| 🔹 **Precision** | 74%       |
| 🔹 **Recall**    | 69%       |

✅ **Key Insights**: The model provides **high AUC (91%)**, indicating strong predictive power in distinguishing churners from non-churners.

## 📌 Future Improvements
🔹 **Hyperparameter Tuning**: Experimenting with different architectures, learning rates, and batch sizes.

🔹 **Feature Engineering**: Adding new derived features to enhance model performance.

🔹 **Ensemble Learning**: Combining ANN with other models (e.g., CatBoost, Random Forest) for improved accuracy.

🔹 **Explainability**: Using SHAP values to interpret feature importance.

## 📢 Contributing
Feel free to contribute by improving the model, refining the dataset, or adding new evaluation metrics! 🚀

🤝 **Contact**: If you have any questions or suggestions, reach out via GitHub Issues or Discussions.

Check out my other projects on my LinkedIn profile: [LinkedIn Profile](https://www.linkedin.com/in/ahmet-yasir-duman-03b689256/)

💡 **If you found this project useful, don’t forget to ⭐ star this repository!** 😊

