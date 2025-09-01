I see your **Mobile Price Prediction** project contains:

* **mobile.csv** → dataset with mobile phone specifications and price ranges
* **Untitled26.ipynb** → Jupyter Notebook with code for analysis, training, and prediction

Here’s a **README description** for your project:

---

# Mobile Price Range Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict the **price range of mobile phones** based on their technical specifications using machine learning algorithms. By analyzing attributes such as RAM, battery power, screen resolution, and storage, the model helps classify phones into different price categories.

## 📂 Dataset

* **File:** `mobile.csv`
* **Description:** Contains specifications of mobile devices, including features such as:

  * Battery Power
  * RAM
  * Screen Resolution
  * Internal Storage
  * Number of Cores
  * Primary & Secondary Camera
  * Connectivity Features
  * Price Range (Target Variable: 0 = Low, 1 = Medium, 2 = High, 3 = Very High)

## ⚙️ Workflow

1. **Data Preprocessing**

   * Handling missing values
   * Feature scaling & normalization
   * Splitting dataset into train and test sets

2. **Exploratory Data Analysis (EDA)**

   * Statistical summary of features
   * Correlation analysis
   * Visualizations using heatmaps and plots

3. **Model Building**

   * Machine Learning algorithms applied:

     * Logistic Regression
     * Decision Tree
     * Random Forest
     * Support Vector Machine (SVM)
     * K-Nearest Neighbors (KNN)
   * Model evaluation using accuracy, precision, recall, and F1-score

4. **Prediction**

   * Predicts the price range of mobile phones based on given features
   * Compares performance of different ML models

## 🛠️ Technologies Used

* **Python**
* **Pandas, NumPy** → Data preprocessing
* **Matplotlib, Seaborn** → Data visualization
* **Scikit-learn** → Machine learning models and evaluation

## 🚀 Results

* Built classification models for mobile price range prediction
* Identified key features influencing mobile pricing
* Achieved high accuracy with ensemble methods like Random Forest

## 📈 Use Cases

* Mobile companies can **forecast pricing strategy** for new devices
* Customers can **compare specifications vs price range** before purchase
* Data science enthusiasts can explore **classification problems** with real-world datasets

