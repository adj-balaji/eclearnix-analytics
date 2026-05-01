# 📊 ECLEARNIX User Analytics & Prediction System

## 🚀 Overview

This project was developed as part of the **ECLEARNIX Hackathon**, focusing on analyzing user behavior, segmenting users, and predicting course completion using machine learning.

It combines:

* Exploratory Data Analysis (EDA)
* User Segmentation using Clustering
* Predictive Modeling
* Business Insights (Marketing ROI)

---

## 🎯 Problem Statement

In e-learning platforms, understanding user engagement and predicting course completion is crucial for:

* Improving user retention
* Enhancing marketing strategies
* Increasing course completion rates

This project provides a **data-driven solution** to these challenges.

---

## ⚙️ Key Features

* 📈 Exploratory Data Analysis (EDA)
* 🧠 User Segmentation using K-Means Clustering
* 🤖 Course Completion Prediction using Random Forest
* 📊 Confusion Matrix & Performance Evaluation
* 💰 Marketing ROI Analysis
* 📉 Correlation Analysis

---

## 🧠 Tech Stack

* Python
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn

---

## 🏗️ Project Workflow

1. Data Loading from Excel dataset
2. Data Preprocessing (categorical conversion, missing handling)
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. User Segmentation (K-Means Clustering)
6. Predictive Modeling (Random Forest Classifier)
7. Model Evaluation (Classification Report + Confusion Matrix)
8. Marketing ROI Analysis

---

## 📊 Key Insights

* 📌 Users are segmented into **3 behavioral clusters**
* 📌 Engagement features like time spent and feedback strongly influence completion
* 📌 Certain marketing channels drive higher course completion rates
* 📌 Predictive model helps identify likely course completers

---

## 📷 Visualizations

### 🔹 Course Completion by Region

![EDA1](images/region_completion.png)

### 🔹 App Installation by Source

![EDA2](images/app_installation.png)

### 🔹 Correlation Heatmap

![EDA3](images/correlation.png)

### 🔹 User Segmentation Clusters

![Clusters](images/clusters.png)

### 🔹 Confusion Matrix

![Confusion](images/confusion_matrix.png)

### 🔹 Marketing ROI

![ROI](images/roi.png)

---

## 🛠️ Installation

```bash id="ec1"
git clone https://github.com/adj-balaji/eclearnix-analytics.git
cd eclearnix-analytics
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash id="ec2"
python main.py
```

---

## 📁 Project Structure

```id="ec3"
ECLEARNIX-Analytics/
│
├── main.py
├── requirements.txt
├── README.md
├── dataset/
│   └── ECLEARNIX_Hackathon_10K_Dataset.xlsx
├── images/
│   ├── region_completion.png
│   ├── app_installation.png
│   ├── correlation.png
│   ├── clusters.png
│   ├── confusion_matrix.png
│   └── roi.png
```

---

## 📈 Model Performance

* Model: Random Forest Classifier
* Good balance between precision and recall
* Effective for structured tabular data

---

## 💡 Business Impact

* 🎯 Identify high-value users
* 📢 Optimize marketing campaigns
* 📈 Improve course completion rates
* 🔍 Understand user engagement patterns

---

## 🚀 Future Enhancements

* Add deep learning models
* Build dashboard using Streamlit
* Real-time prediction system
* A/B testing for marketing strategies

---

## 👨‍💻 Author

**BALAJI A D J**
GitHub: https://github.com/adj-balaji

---

## 🏆 Hackathon Project

Developed for **ECLEARNIX Hackathon**

---

## ⭐ Give a star if you like this project!
