# Federated Learning for Diabetic Retinopathy Detection

This project implements a **Federated Learning (FL)** approach for **Diabetic Retinopathy (DR) classification** using deep learning.  
Instead of centralizing sensitive medical data, models are trained locally on distributed datasets and only the model weights are shared with the central server using **Federated Averaging (FedAvg)**.  

The goal is to build a **privacy-preserving, scalable, and robust** DR detection system that can be deployed across multiple hospitals or devices without sharing raw patient data.

---

## 🚀 Features
- **Teacher–Student Models** for collaborative learning.
- **MobileNetV2 backbone** for efficient image classification.
- **Manual implementation of Federated Averaging (FedAvg)**.
- **Handles class imbalance** with oversampling, weighted loss, and augmentations.
- Comparison between:
  - Centralized training  
  - Federated training  

---



## 🛠️ Tech Stack
- **Python 3.x**
- **TensorFlow / Keras**
- **NumPy, Pandas**
- **Matplotlib / Seaborn**
- **Scikit-learn**

---

## ⚙️ Federated Learning Workflow
1. **Data Partitioning** – dataset is split across multiple simulated clients.  
2. **Local Training** – each client trains its model on its own data.  
3. **Federated Averaging (FedAvg)** – local model weights are averaged by the central server.  
4. **Global Update** – aggregated model is shared back with clients for the next round.  

---

## 📊 Results
- Evaluated on **Diabetic Retinopathy datasets**.  
- Metrics: **Accuracy, Precision, Recall, F1-score**.  
- Comparisons made between **centralized and federated setups**.  

(📌 Add plots/results here once finalized.)

---

## 🔮 Future Work
- Extend to **multi-institutional datasets**.  
- Integrate with **blockchain** for secure model update tracking.  
- Experiment with **advanced federated optimizers**.  

---
