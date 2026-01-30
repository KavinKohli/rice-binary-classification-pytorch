# Rice Binary Classification using PyTorch ANN

## Overview
This project performs **binary classification of rice samples** using an **Artificial Neural Network (ANN)** implemented with **PyTorch**.  
It represents a complete **end-to-end machine learning pipeline**, covering data preprocessing, feature scaling, model training, evaluation, and prediction.

The objective is to accurately classify rice samples into two classes based on their extracted features.

---

## Dataset
The dataset consists of **tabular rice feature data** used for binary classification.

| Feature | Description |
|--------|-------------|
| Feature 1 | Rice grain characteristic |
| Feature 2 | Rice grain characteristic |
| Feature 3 | Rice grain characteristic |
| ... | ... |
| Feature N | Rice grain characteristic |
| Label | 0 = Class A, 1 = Class B |

> The dataset is preprocessed and normalized before training the neural network.

---

## Project Workflow
1. Data loading  
2. Feature preprocessing  
3. Feature scaling using StandardScaler  
4. Train-test split  
5. ANN model definition using PyTorch  
6. Model training  
7. Model evaluation  
8. Prediction and performance analysis  

---

## Artificial Neural Network Model
The project uses a **fully connected Artificial Neural Network (ANN)** with:
- Linear (Dense) layers  
- ReLU activation function  
- Sigmoid activation for binary output  

The model is trained using:
- **Binary Cross Entropy Loss**
- **Adam Optimizer**

---

## Model Performance
The model is evaluated using:
- Accuracy  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)  

The trained model demonstrates effective performance on unseen test data.

---

## 🛠️ Technologies Used
- Python  
- PyTorch  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  

---

## How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/KavinKohli/rice-binary-classification-pytorch.git
cd rice-binary-classification-ann-pytorch
