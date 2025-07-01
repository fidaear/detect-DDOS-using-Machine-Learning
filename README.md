# 🔐 DDoS Attack Detection using Machine Learning

This project uses supervised Machine Learning algorithms to detect DDoS (Denial of Service) attacks in Wireless Sensor Networks (WSNs). The goal is to distinguish between normal and malicious traffic using classification models.

## 📊 Dataset

- **WSN-DS** dataset
- Contains labeled data for normal and DDoS traffic
- Features include packet length, time intervals, and other network metrics

## ⚙️ Algorithms Used

- ✅ Random Forest
- ✅ Logistic Regression
- ✅ Neural Networks

Each model is trained and evaluated to compare accuracy and performance.

## 🧠 Main Steps

1. **Data Preprocessing**
   - Cleaning, feature selection, and normalization
2. **Model Training**
   - Train ML models on training data
3. **Evaluation**
   - Test accuracy, confusion matrix, and F1-score
4. **Prediction**
   - Detect whether incoming traffic is normal or an attack

## 📁 Project Structure

│
├── data/ # WSN-DS dataset files
├── models/ # Trained models (optional)
├── src/ # Python source code
│ ├── preprocessing.py
│ ├── train.py
│ ├── evaluate.py
│ └── predict.py
├── results/ # Accuracy reports, confusion matrices
├── README.md
└── requirements.txt # Python dependencies
