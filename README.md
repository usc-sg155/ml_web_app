**Machine Learning Health Prediction App**

Overview
This web application utilizes machine learning models to predict health conditions related to diabetes, heart disease, and Parkinson's disease. The app is deployed using Streamlit.io, making it accessible for easy and interactive predictions.

https://mlwebapp.streamlit.app/

Models
The application includes the following pre-trained machine learning models:

Diabetes Model

Model File: diabetes_model.sav
Description: Predicts the likelihood of diabetes based on input features.
Heart Disease Model

Model File: heart_disease_model.sav
Description: Predicts the presence of heart disease using relevant health parameters.
Parkinson's Model

Model File: parkinsons_model.sav
Description: Predicts the probability of Parkinson's disease based on input features.
Files
mdps.py: This is the main Python script containing the Streamlit web application code.

requirements.txt: Lists the required Python packages and their versions.

How to Run the App
Clone the repository to your local machine.

bash
Copy code
git clone https://github.com/your-username/your-repo.git
cd your-repo
Install the required packages using pip.

bash
Copy code
pip install -r requirements.txt
Run the Streamlit app.

bash
Copy code
streamlit run mdps.py
Access the app in your browser at the provided URL (usually http://localhost:8501).

![Screenshot 2024-02-06 at 9 47 44 pm](https://github.com/usc-sg155/ml_web_app/assets/48895382/998b15b7-8d8a-4564-a078-d534cd54af30)

Usage
Upon running the app, you'll be presented with a user-friendly interface.
Input the necessary health parameters for the desired prediction.
Click the corresponding button to obtain predictions for diabetes, heart disease, or Parkinson's disease.
