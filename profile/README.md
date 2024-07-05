<h1 align="center">🔋 Remaining Useful Life (RUL) Prediction 🔋</h1>

## 📝 Introduction

The urgency to explore and develop new energy sources stems from the ongoing conventional energy crisis. **Lithium-ion batteries** have become prominent due to their high energy density, output voltage, extended cycle life, and broad operating temperature range. 

However, repeated charging and discharging cycles increase internal resistance, causing overheating and deteriorating performance. The **Remaining Usable Life (RUL)** of a lithium-ion battery refers to the number of cycles left from the start of measurement to the end of its life (EOL).

---

## 🧩 Overview

Lithium-ion batteries display **nonlinear degradation** patterns, including capacity fading, resistance increase, and power drop, even under ideal conditions. To predict RUL accurately, one must consider these behaviors to avoid overfitting.

Key aspects of effective RUL prediction include:

- **Activation Function**
- **Training Procedure**
- **Hyperparameter Tuning**
- **Uncertainty Management**
- **Resilience**

---

## 💡 Machine Learning Model

The **Transformer** model is highly effective for RUL prediction due to its strength in handling long sequences and small datasets, along with providing probabilistic outputs. However, it can be computationally demanding and requires careful hyperparameter tuning to avoid overfitting.

---

## 📊 Result Analysis & Dataset

We utilized a publicly available dataset from NASA Ames Research Center. This dataset contains records of four different Li-ion batteries, each undergoing repeated measurements of impedance, charge, and discharge.

---

## 📈 Evaluation Metrics

To assess the prediction performance of RUL, the following metrics were employed:

- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **Relative Error (RE)**

These metrics provide insights into the accuracy and reliability of the predictions.

---

## 📉 Actual vs. Predicted RUL

Here is a comparison between the actual and predicted RUL:

<p align="center">
  <img src="https://github.com/Minor-Project-6th-Semester/RUL-prediction-methods/assets/94170547/f6543f6d-29ac-420e-b2cc-c2cd3e05e05e" alt="Actual vs Predicted RUL" width="100%">
</p>

---

## 📚 References

- NASA Ames Research Center [Lithium-ion Battery Data](https://www.nasa.gov/content/research-datasets)

---

