# HRLFD – Hybrid Reinforcement Learning for Fraud Detection  

This repository contains a research project exploring how **reinforcement learning (RL)** can be combined with traditional **machine learning classifiers** to improve fraud detection in highly imbalanced datasets.  

## ⚡ Features
- **Q-Learning agent** trained to maximize fraud detection performance  
- **Decision tree ensemble** for candidate filtering  
- **Custom reward function** designed to penalize false negatives heavily  
- **SMOTE resampling** for balancing rare fraud cases  
- **Evaluation metrics** including precision, recall, F1-score, and ROC AUC  

## 📦 Tech Stack
- **Python** → Core implementation  
- **scikit-learn** → Decision trees, evaluation metrics  
- **imbalanced-learn** → SMOTE resampling  
- **NumPy / Pandas** → Data manipulation  
- **Matplotlib / Seaborn** → Visualization  
