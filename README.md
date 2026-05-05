# 🏠 House Price Prediction

> Predict the price of a house based on its features using Supervised Machine Learning Regression algorithms.

---

## 📌 About the Project

Ever wondered what a house is actually worth? Whether you're a **buyer** or a **seller**, knowing the fair price of a house is never easy.

This project uses **supervised machine learning regression algorithms** to predict house prices based on key features of the target house — no guesswork, just data.

Simply provide the features of the house, and let the model do the work.

---

## 🎯 Problem Statement

> *"If you are a buyer or seller of a house but don't know the exact price — regression algorithms can help you predict it by just providing the features of the target house."*

---

## 📂 Dataset

| Split | Rows | Columns |
|-------|------|---------|
| Training set | 1460 | 81 |
| Test set | 1459 | 80 |

- Features include: location, size, number of rooms, condition, year built, and more.
- Target variable: **Sale Price**

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 🔄 Project Workflow

```
Data Collection → EDA → Data Preprocessing → Model Training → Model Evaluation → Prediction
```

### Steps followed:
1. **Exploratory Data Analysis (EDA)** — understanding distributions, correlations & outliers
2. **Data Preprocessing** — handling missing values, encoding categorical features, scaling with `StandardScaler`
3. **Model Training** — training multiple regression models and tracking scores
4. **Model Evaluation** — comparing models using performance metrics
5. **Prediction** — predicting house prices on unseen test data

---

## 📁 Repository Structure

```
house_prediction_project/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── EDA_img/                        # EDA visualizations
│
├── house_price_prediction.ipynb    # Main notebook
├── python_number_methon.ipynb      # Supporting notebook
│
└── README.md
```

---

## 📊 Models Used

| Model | Description |
|-------|-------------|
| Linear Regression | Baseline regression model |
| Ridge Regression | L2 regularization to reduce overfitting |
| Lasso Regression | L1 regularization for feature selection |
| Random Forest | Ensemble method for better accuracy |

---

## ▶️ How to Run

1. Clone the repository
```bash
git clone https://github.com/shreshthasharma110/house_prediction_project.git
```

2. Install dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Open the notebook
```bash
jupyter notebook house_price_prediction.ipynb
```

---

## 👩‍💻 Author

**Shreshtha Sharma**
CSE Undergrad '28 | Python & ML Enthusiast

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shreshtha-sharma-413bb232b)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shreshthasharma110@gmail.com)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shreshthasharma110)

---

> *"This is one of my first ML projects — built to learn, improve, and grow. Feedback is always welcome!"* 🙌
