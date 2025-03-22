# AI-Powered Medical Diagnosis App

## Overview
The **AI-Powered Medical Diagnosis App** is a **Streamlit-based web application** that predicts the likelihood of diseases based on user-provided medical parameters. It utilizes **Machine Learning models** trained on medical datasets to assist in early diagnosis.

## Features
- **User Input Form**: Enter medical parameters related to diseases such as heart disease, Parkinson’s, thyroid, and lung cancer.
- **Data Preprocessing**: Cleans and prepares medical data for machine learning predictions.
- **Machine Learning Models**: Uses **Support Vector Machine (SVM), Logistic Regression, and Random Forest** for classification.
- **Real-Time Predictions**: Provides disease risk assessment based on user inputs.
- **Interactive UI**: Developed with **Streamlit** for an intuitive experience.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/medical-diagnosis.git
    cd medical-diagnosis
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the application:
    ```bash
    streamlit run app.py
    ```

## Data Requirements
- The medical dataset should be in **CSV format** and placed in the project directory.
- The dataset should include parameters such as **Age, Gender, Symptoms, Test Results, and Diagnosis Status**.

## Usage
1. Enter your medical details in the provided form.
2. The model processes your input and predicts the likelihood of diseases.
3. View diagnosis results and possible risk factors.

## Dependencies
- `streamlit`
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`

## Future Enhancements
- Integrate **Deep Learning** for more accurate predictions.
- Support **additional diseases** and expand dataset sources.
- Deploy the app on **cloud platforms** for wider accessibility.

---

🚀 **Developed with Machine Learning and Streamlit for Medical Diagnosis**
