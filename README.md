# Fraud-Detection-using-Machine-Learning
Detecting fraudulent online transactions using machine learning with the IEEE-CIS Fraud Detection dataset. This project builds and evaluates models to predict fraud, helping reduce financial risk and improve e-commerce security through data-driven insights.
# IEEE-CIS Fraud Detection - Capstone Project

This project is a capstone submission for the IEEE-CIS Fraud Detection competition on Kaggle. The objective is to build a machine learning model to identify fraudulent online transactions based on a large, real-world e-commerce dataset provided by Vesta Corporation.

**Team Members:**
- Bharadwaja Addanki
- Mohammed Hassan Ahmed
- Swagath Banda
- Vijay Kumar Vemana

---

## 📖 Project Overview

This project tackles the challenge of identifying fraudulent online transactions using machine learning techniques. Fraudulent transactions lead to significant financial losses, and by leveraging data science, we can enhance security and build trust in e-commerce.

The core of this project involves:
- **Data Exploration & Preprocessing:** Handling a large dataset with numerous features and significant missing values.
- **Feature Engineering:** Creating meaningful features from transactional and identity data.
- **Model Building:** Implementing and evaluating several classification models, including Logistic Regression, Random Forest, and XGBoost.
- **Evaluation:** Using metrics like the Area Under the Curve (AUC) to measure model performance, with a final competition score of **0.8766**.

---

## 🛠️ Technologies & Libraries Used
- **Python 3**
- **Pandas & NumPy:** For data manipulation and numerical operations.
- **Scikit-learn:** For data preprocessing and building Logistic Regression and Random Forest models.
- **XGBoost:** For building the primary gradient-boosted model.
- **Jupyter Notebook:** For analysis and reporting.

---

## 🚀 How to Run This Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/ieee-fraud-detection-capstone.git](https://github.com/YOUR_USERNAME/ieee-fraud-detection-capstone.git)
    ```
2.  **Download the Data:**
    The data for this project is from the [IEEE-CIS Fraud Detection Kaggle Competition](https://www.kaggle.com/c/ieee-fraud-detection/data). You will need to download it from Kaggle and place the `.csv` files in a `data/` subfolder.

3.  **Install Dependencies:**
    Install the necessary Python libraries using pip:
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the Notebooks:**
    Launch Jupyter Notebook and open the `ieee-final-report.ipynb` or `xgboost-model.ipynb` files to see the analysis and model-building process.****
