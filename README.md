# Credit-Card-detection
This project is based on machine learning and neural network algorithm and is efficient in finding credit card fraud detection 

# 💳 Credit Card Fraud Detection Using Neural Networks

This project detects fraudulent credit card transactions using a neural network model trained on the popular Kaggle dataset. The dataset is highly imbalanced, so appropriate techniques like resampling were used to balance the classes before training.

---

##  Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Samples**: 284,807 transactions
- **Fraud cases**: ~0.17% only

---

##  Model Overview

- **Architecture**: Fully Connected Neural Network (Keras Sequential API)
- **Techniques used**:
  - Data normalization (RobustScaler for `Amount`, MinMax for `Time`)
  - Class balancing (undersampling of non-fraudulent data)
  - Early stopping and model checkpointing

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- TensorFlow / Keras
- scikit-learn

---

## 📈 Results

- Achieved high precision and recall on fraud detection.
- Evaluation via confusion matrix and classification report.
- Custom visualization heatmaps included.

---




