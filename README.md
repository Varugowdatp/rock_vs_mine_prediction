# 🪨 Rock vs Mine Prediction

This project is a **Machine Learning classification model** that predicts whether a sonar return signal is from a **rock** or a **mine** (metal cylinder).  
The dataset used is the **Sonar Dataset** from the **UCI Machine Learning Repository**.

---

## 📘 Project Overview

Underwater sonar signals are used to identify objects such as rocks or mines (metal objects).  
This project applies supervised learning algorithms to classify sonar signals based on their frequency response.

---

## 🧠 Objective

To build a **binary classification model** that can predict:
- **Rock (R)** — when the sonar signal is reflected off a rock.
- **Mine (M)** — when the sonar signal is reflected off a metal object (mine).

---

## 🧩 Dataset Details

- **Source:** UCI Machine Learning Repository — *Sonar Mines vs. Rocks Dataset*
- **Number of Instances:** 208  
- **Number of Attributes:** 60 continuous features  
- **Target Variable:** `R` or `M`  

Each feature represents the energy within a particular frequency band of the sonar signal.

---

## ⚙️ Technologies Used

- Python 🐍  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 🧮 Steps Performed

1. **Data Loading and Exploration**
   - Checked shape, info, and distribution of the dataset.
   - Visualized target class balance.

2. **Data Preprocessing**
   - Converted target labels into numeric format.
   - Split dataset into training and testing sets.

3. **Model Training**
   - Trained using **Logistic Regression** (or SVM / Random Forest if tested).
   - Performed standardization using `StandardScaler`.

4. **Model Evaluation**
   - Evaluated using **Accuracy**, **Confusion Matrix**, and **Classification Report**.
   - Compared model performance between train and test sets.

5. **Prediction**
   - Implemented a prediction example to test on new sonar signal input.

---

## 📊 Results

| Metric | Train Accuracy | Test Accuracy |
|:-------:|:---------------:|:--------------:|
| Logistic Regression | ~85-90% | ~83-87% |

*(Values may vary slightly based on random seed.)*

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Varugowdatp/rock_vs_mine_prediction.git
2. Run it from respective repo.
