# Heart Disease Predictor Web App

This project is a machine learning-based web application built using Streamlit that predicts the likelihood of heart disease based on user input. It provides both individual and bulk prediction capabilities, along with model performance visualization.

## Features

Manual Heart Disease Prediction
Users can input their health parameters such as age, blood pressure, cholesterol, etc., and instantly get predictions about heart disease risk.

Bulk Predictions
Upload a CSV file containing multiple patient records to generate predictions in one go. This feature is useful for healthcare professionals and data analysis tasks.

Model Accuracy Visualization
The app displays performance comparison of different machine learning models including Logistic Regression, Decision Trees, Random Forest, Support Vector Machine, and Grid Search Random Forest.

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine
* Grid Search Random Forest

## Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Plotly

## How to Run Locally

1. Clone the repository

2. Install dependencies:

   pip install -r requirements.txt

3. Run the app:

   streamlit run app.py

## How to Use

Manual Prediction

* Go to the "Predict" tab
* Enter the required health parameters
* Click submit to view results

Bulk Prediction

* Go to "Bulk Predict" tab
* Upload CSV file with correct format
* Download predictions file

## CSV Format for Bulk Upload

Columns required:

Age, Sex, ChestPainType, RestingBP, Cholesterol, FastingBS, RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope

Make sure:

* No missing values
* Correct column names
* Correct data encoding

## Project Structure

app.py – main Streamlit application
requirements.txt – dependencies
.pkl files – trained machine learning models
sample_data.csv – sample input file

## Future Improvements

* Improve UI/UX
* Add more advanced models
* Deploy with database support
* Add real-time data integration

## Disclaimer

This project is for educational purposes only and should not be used as a substitute for professional medical advice.
