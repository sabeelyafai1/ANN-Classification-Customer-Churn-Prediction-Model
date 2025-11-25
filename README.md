# ANN-Classification-Coustomer-Churn-Prediction-Model


This project implements an **Artificial Neural Network (ANN)** for predicting **customer churn** based on customer behavior and service usage features.  
The model is developed using **TensorFlow**, **Keras**, **Scikit-Learn**, **Pandas**, and includes:

✔ Hyperparameter tuning  
✔ TensorBoard visualization  
✔ Streamlit deployment  

👉 **The final model is also deployed as a Streamlit web app for real-time churn prediction.**

---

## 📌 Project Objectives

- Build an ANN classification model to predict customer churn  
- Preprocess customer-related data  
- Tune hyperparameters to optimize performance  
- Use **TensorBoard** to visualize training metrics  
- Deploy the model using **Streamlit**  
- Provide a user-friendly web interface for predictions  

---

## 🧠 Technologies & Libraries Used

- **Python 3.x**
- **TensorFlow**
- **Keras**
- **Scikit-Learn**
- **Pandas**
- **NumPy**
- **TensorBoard** ← (for real-time training visualization)
- **Streamlit** (for web deployment)
- **Matplotlib / Seaborn**

---


---

## 🔧 How the Model Works

### **1. Data Preprocessing**
- Handle missing values  
- Encode categorical columns (LabelEncoder / OneHotEncoder)  
- Train-test split  
- Apply StandardScaler for normalization  

---

### **2. ANN Classification Architecture**

- **Input Layer**
- **Hidden Layer 1** – Dense + ReLU  
- **Hidden Layer 2** – Dense + ReLU  
- **Output Layer** – Sigmoid activation for binary classification  

---

### **3. Hyperparameter Tuning**
Hyperparameters tuned include:

- Number of hidden layers  
- Neuron count  
- Activation functions  
- Learning rate  
- Optimizer  
- Batch size & epochs  
- Dropout (if tested)

Tools used:

- **GridSearchCV / RandomizedSearchCV**  
- **KerasClassifier wrappers**


---

## 📊 TensorBoard Visualization

**TensorBoard** was used to visualize:

- Training & validation loss  
- Training & validation accuracy  
- Learning rate changes  
- Hyperparameter performance  
- Model graph structure  



