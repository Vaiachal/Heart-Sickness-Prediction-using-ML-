# Heart-Sickness-Prediction-using-ML-

Overview:
A classy and simple in design  web application which uses Machine Learning algorithms to predict the heart condition of a person by providing some inputs about the person health like age, gender, blood pressure, cholesterol level etc built using Flask and deployed on Heroku. and in thier we are going to use the obtained the dataset from Kaggle. It has patient medical records with 13 parameters/columns useful to predict heart health.

The 13 parameters which are given in the datset used to predict if a person has heart disease or not are:
- age : The person's age in years
- sex : The person's sex (1 = male, 0 = female)
- cp : The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
- trestbps : The person's resting blood pressure (mm Hg on admission to the hospital)
- chol : The person's cholesterol measurement in mg/dl
- fbs : The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
- restecg : Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalach : The person's maximum heart rate achieved
- exang : Exercise induced angina (1 = yes; 0 = no)
- oldpeak : ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot)
- slope : the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
- ca : The number of major vessels (0-3)
- thal : A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect) 

The last column in the dataset "target" represents if a person has hear disease or not (1 = Heart disease, 0 = No Heart disease).

After training and testing the dataset with KNN, Random forest , Logistic Regression and Linear Regression and Naive Bayes and comparing their accuracies, chose to use Logistic Regression for implentation.and as to increase the efficency and expectation about ease of access.

Technical Details:
Then saved this model and using Flask for backend linked this model to a website.
Exploring the dataset and traning the model using Sklearn.
Users can just enter the 13 parameters in the form and press submit to obtain the probability of whether their heart is prone to any disease or not.

Installation
The project's code is written in Python 3.8. If you do not have Python installed, please download and install it from the official Python website. If you are using an older version of Python, you can upgrade it by using the pip package manager. Ensure that you have the most recent version of pip installed.To set up the project, navigate to the project directory after cloning the repository and execute the following command:

pip install -r requirements.txt 
This command will install all the necessary packages and libraries specified in the requirements.txt file.

![Screenshot 2023-06-13 004821](https://github.com/Vaiachal/Heart-Sickness-Prediction-using-ML-/assets/118053698/24fddfc1-18ba-42a0-9f24-46ca0984e3c9)

![Screenshot 2023-06-13 005109](https://github.com/Vaiachal/Heart-Sickness-Prediction-using-ML-/assets/118053698/e8dc2323-a7dc-478d-ba03-7146b4a442b1)
