# Credit Card Transaction Fraud Detection using Classification

## 📌 Project Overview  
This project focuses on detecting fraudulent credit card transactions using **Classification**. The dataset used is highly imbalanced, containing real-world anonymized transaction data. The goal is to build a classification model that can effectively distinguish between fraudulent and legitimate transactions.  

## 📂 Dataset  
The dataset is sourced from Kaggle: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download).  
- The dataset contains **284,807 transactions**, out of which only **492 (0.172%)** are fraudulent.  
- Features include **V1 to V28** (anonymized using PCA), along with **Time, Amount**, and the **Class label** (0 for legitimate, 1 for fraud).  

## 🏗️ Project Workflow  
1. **Data Preprocessing**  
   - Handling class imbalance data
   - Feature scaling for better model performance  

2. **Exploratory Data Analysis (EDA)**  
   - Understanding feature distributions  
   - Visualizing fraud vs. legitimate transactions  

3. **Model Training & Evaluation**  
   - Training a **Classification**  
   - Evaluating using **accuracy, precision, recall, F1-score** 
