# EMIPredict AI - Intelligent Financial Risk Assessment Platform

[![Streamlit App](https://img.shields.io/badge/Streamlit-Share-red?logo=streamlit)](YOUR_STREAMLIT_APP_URL_HERE)

A machine learning-powered platform to solve the critical issue of financial risk assessment for EMI (Equated Monthly Instalment) payments. This tool provides data-driven insights for better loan decisions, helping both financial institutions and customers.

### 🎯 Problem Statement

Nowadays, many people struggle to pay EMIs due to poor financial planning and inadequate risk assessment. This project builds a comprehensive, interactive web application that integrates machine learning models to predict:
1.  **EMI Eligibility (Classification):** Whether a customer is 'Eligible', 'High_Risk', or 'Not_Eligible'.
2.  **Maximum EMI Amount (Regression):** The maximum safe monthly EMI a customer can afford.

---

### ✨ Key Features

* **Dual ML Problem Solving:** Implements both classification and regression models to provide a complete financial picture.
* **Real-time Risk Assessment:** Instantly predicts eligibility and affordable EMI amounts using 22 financial and demographic variables.
* **Experiment Tracking:** Integrates **MLflow** for comprehensive tracking, comparison, and versioning of all model experiments.
* **Interactive Web App:** A multi-page **Streamlit** application that is intuitive, user-friendly, and deployed on the cloud.
* **Data-Driven Insights:** Includes a dashboard for visualizing data patterns and model performance.

---

### 🛠️ Tech Stack & Architecture

* **Programming Language:** Python
* **Data Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn, XGBoost
* **Experiment Tracking:** MLflow
* **Web Framework:** Streamlit
* **Deployment:** Streamlit Cloud

#### Data Flow
Dataset (400K Records) → Data Preprocessing → Feature Engineering → ML Model Training (MLflow Tracking) → Model Selection → Streamlit Application → Cloud Deployment

---

### 🔧 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    cd YOUR_REPOSITORY_NAME
    ```

2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Launch the MLflow server (Optional, for tracking):**
    ```bash
    mlflow ui
    ```

5.  **Run the Streamlit app:**
    ```bash
    streamlit run Home.py
    ```
    The application will open in your browser at `http://localhost:8501`.

---

### 📂 Project Structure
