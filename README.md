# Customer Churn Prediction

### End-to-End Machine Learning + Deep Learning Application

A machine learning project that predicts whether a customer is likely to **churn (leave the service)** based on various features such as age, balance, credit score, and activity status.

This project demonstrates a complete pipeline from **data preprocessing to model deployment using a Streamlit web application**.

---

## Features

### Data Processing
* Handling missing values  
* Encoding categorical variables  
* Feature scaling using StandardScaler  

### Machine Learning / Deep Learning
* Neural Network model (TensorFlow / Keras)  
* Training on structured customer dataset  
* Probability-based prediction  

### Application
* Interactive Streamlit web app  
* User input for real-time prediction  
* Displays churn probability and result  

---

## Tech Stack
* **Python**
* **TensorFlow / Keras**
* **NumPy**
* **Pandas**
* **scikit-learn**
* **Streamlit**

---

## System Architecture


Customer Data

↓

Data Preprocessing

↓

Encoding (Label + OneHot)

↓

Feature Scaling

↓

Model Training

↓

Prediction

↓

Churn Probability Output


---

## Project Workflow

1. Load customer dataset  
2. Perform preprocessing and feature engineering  
3. Encode categorical variables  
4. Scale numerical features  
5. Train deep learning model  
6. Save model and preprocessing objects  
7. Build Streamlit app  
8. Predict churn based on user input  

---

## Repository Structure


Customer-Churn-Prediction/
│

├── app.py

├── model.h5

├── Churn_Modelling.csv
│

├── encoders/

│   ├── label_encoder_gender.pkl

│   ├── onehot_encoder_geo.pkl

│   ├── scaler.pkl
│

├── notebooks/

│   ├── Project_prediction.ipynb

│   ├── Project_salary_regression.ipynb

│   ├── Project_experiments.ipynb

│
├── requirements.txt



---

## Key Concepts Covered
* Feature engineering on structured data  
* Encoding categorical variables  
* Feature scaling  
* Neural networks for classification  
* End-to-end ML pipeline  
* Model deployment using Streamlit  

---

## Installation

git clone https://github.com/YOUR_USERNAME/Customer-Churn-Prediction.git  
cd Customer-Churn-Prediction  

---

## Usage

streamlit run app.py  

---

## Example

Input: Customer details (age, balance, credit score, etc.)  
Output: Churn probability and prediction  

---

## Future Improvements

* Hyperparameter tuning  
* Model comparison (ML vs DL)  
* Improved feature engineering  
* Deployment on cloud platforms  

---

## Author

Mohammed Anas  
B.Tech IT Student | AI & ML Enthusiast
