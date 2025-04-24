🩺 Diabetes Prediction using Machine Learning
This project focuses on predicting whether a person is diabetic based on certain medical attributes using machine learning algorithms. It utilizes a publicly available dataset from Kaggle and demonstrates the complete ML pipeline from data preprocessing to model deployment with an interactive UI built using Gradio.

📂 Dataset
The dataset used is the Diabetes Database from Kaggle. It consists of 768 observations with 8 independent variables and 1 target variable. The attributes include:
Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skinfold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: A function that scores the likelihood of diabetes based on family history
Age: Age in years
Outcome: Class variable (0: Non-diabetic, 1: Diabetic)

🧠 Machine Learning Models Used
Three machine learning models were trained and evaluated:


Model	Accuracy Score
Logistic Regression	0.7857
Decision Tree Classifier	0.7143
Random Forest Classifier	0.7792
Based on accuracy score, Logistic Regression was selected as the best performing model.

🚀 Deployment
The best model (LogisticRegression) was deployed using Gradio to create an interactive web UI for real-time diabetes prediction.
Users can input the values for medical attributes and get an instant prediction on whether the person is likely to have diabetes.

💻 How to Run
Clone the repository:

bash

Copy

git clone https://github.com/Arati9703/Diabetes_detection

cd diabetes-prediction

Install dependencies:

bash
Copy

pip install -r requirements.txt

Run the Gradio app:

bash

Copy

python app.py

🧾 Requirements
Python 3.x
scikit-learn
pandas
numpy
gradio

