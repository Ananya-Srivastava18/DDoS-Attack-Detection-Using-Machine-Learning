# 🚨 DDoS Attack Detection Using Machine Learning

## 📘 Overview

A Distributed Denial of Service (DDoS) attack is a cyber-attack where multiple compromised systems flood a targeted server, website, or network with excessive traffic or requests, rendering it inaccessible to legitimate users. These systems, often infected with malware and turned into botnets, overwhelm the target, leading to service disruption.

DDoS attacks can cause significant financial loss, reputational damage, and erosion of customer trust. Hence, detecting and mitigating these attacks is vital for maintaining the integrity and availability of networked systems.

This project focuses on detecting DDoS attacks using various machine learning algorithms. It uses the **IDS 2017 dataset** and includes all major steps such as data preprocessing, exploration, model training, and evaluation. The goal is to build an accurate and efficient classifier for early DDoS detection.

---

## 📂 Table of Contents

1. Importing Libraries  
2. Data Pre-processing  
3. Data Exploration  
4. Data Splitting  
5. Model Training  
   - Random Forest  
   - Logistic Regression  
6. Model Evaluation  
   - Accuracy  
   - F1 Score  
   - Recall  
   - Precision  
   - Confusion Matrix  
7. Model Comparison  

---

## 🛠️ Dataset

- **Name**: IDS 2017 (Intrusion Detection System 2017)
- **Source**: [Kaggle - DDoS Datasets](https://www.kaggle.com/datasets/devendra416/ddos-datasets)
- **Description**: Contains labeled network traffic data for training machine learning models to detect DDoS attacks.

---

## 🤖 Machine Learning Models Used

- **Random Forest Classifier**
- **Logistic Regression**

These models were chosen for their robustness and efficiency in classification problems involving network traffic data.

---

## 📊 Evaluation Metrics

To measure and compare the performance of each model, we used the following metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

---

## ✅ Results
![image](https://github.com/user-attachments/assets/3cce3d58-49e3-49c9-a729-c3ce5f62cee4)
![image](https://github.com/user-attachments/assets/0011c283-9ec3-4e7f-bd8d-b71ba072de27)
![image](https://github.com/user-attachments/assets/12dac410-b9c1-4464-a2cc-67cd43385352)
---

## 📌 Conclusion

This project demonstrates how machine learning models can effectively classify DDoS attacks using real-world network traffic data. Random Forest and Logistic Regression classifiers were implemented and evaluated, with comparative results offering insights into their effectiveness.

---
