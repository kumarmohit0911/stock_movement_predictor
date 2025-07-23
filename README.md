# 📈 Stock Movement Prediction using ANN

This project uses a deep learning model (Artificial Neural Network) to predict whether a stock's price will go up or down based on historical features like Open, Close, High, Low, Volume, and EWMA (Exponentially Weighted Moving Average).

---

## 🚀 Model Overview

- **Architecture**: Fully connected neural network with dropout and ReLU activations.
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Batch Size**: [Specify here if known]
- **Epochs**: [Specify here]
- **Framework**: Keras (TensorFlow backend)

---

## 📊 Features Used

- Open Price
- Close Price
- High
- Low
- Volume
- EWMA (Exponential Weighted Moving Average)

---

## 🧠 Labels

The label column (`new_col`) is binary:
- `1` → Stock went up
- `0` → Stock went down

---

## 📈 Performance

| Metric                 | Value     |
|------------------------|-----------|
| Accuracy               | 74.20%    |
| Mean Absolute Error    | 0.385     |
| Mean Squared Error     | 0.179     |

---

## 🔧 Installation

```bash
git clone https://github.com/yourusername/stock-updown-predictor.git
cd stock-updown-predictor
pip install -r requirements.txt
