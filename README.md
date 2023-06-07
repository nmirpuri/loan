# Loan Prediction Web Application using ML
The Loan Prediction Web Application is a web-based tool that predicts loan approval based on user input. It utilizes a machine learning model to provide an estimated outcome for loan applications. This project aims to assist individuals and financial institutions in making informed decisions regarding loan approvals.

# Dataset used for model training
https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset

# Features
* User-friendly Interface: The web application offers a simple and intuitive user interface where users can easily input their information.

* Prediction: Once the user submits their details, the application processes the input and provides a prediction regarding loan approval.

* Model Integration: The application integrates a pre-trained machine learning model that has been trained on historical loan data.

* Customizability: The project provides flexibility for users to customize and improve the prediction model according to their specific requirements.

* Scalability: The web application is built using the Express.js framework, ensuring scalability to handle a large number of concurrent users.

# Technologies Used
* Node.js: The server-side runtime environment that powers the web application.
* Express.js: A fast and minimalist web framework for Node.js that handles routing and middleware.
* EJS: A templating engine that enables dynamic content rendering on the server.
* Python: The programming language used for machine learning model training and prediction.
* Pandas: A powerful data manipulation library in Python for handling structured data.
* scikit-learn: A popular machine learning library in Python that provides various algorithms and tools for model training and evaluation.
* Joblib: A Python library used for serializing and deserializing machine learning models.
* Git: Version control system for managing project codebase.

# Prerequisites
Before running the application, make sure you have the following installed:
* Node.js
* Python
* pip 
* npm

# Installation
1.Clone the repository:
```
git clone https://github.com/viveklistenus/Loan_Prediction_Web_Application.git
```
2.Install the required Node.js dependencies:
```
cd loan-prediction-web-app
npm init
npm install
```
# Usage
* Start the Node.js server:
```
node server.js
```
* Access the web application in your browser at http://localhost:3000.
* Fill out the loan prediction form with the required information.
* Click the "Submit" button.
* The application will process the input and display the prediction result.

# Screenshots
![1](https://github.com/viveklistenus/Loan_Prediction_Web_Application/assets/28853520/04542ba5-eeef-48d7-97ec-d6893a3a688f)

![2](https://github.com/viveklistenus/Loan_Prediction_Web_Application/assets/28853520/b7b295d7-0b30-4ee4-b24a-e8f2d5b4ecac)

![3](https://github.com/viveklistenus/Loan_Prediction_Web_Application/assets/28853520/ccac12e9-be12-4ba2-8b8e-aa8459b82dc7)

![4](https://github.com/viveklistenus/Loan_Prediction_Web_Application/assets/28853520/fa10284c-88f9-4b91-a7b8-8f1d63b9b9a9)

# Customization
If you want to customize or improve the model, follow these steps:

* Modify the loan_prediction.py file to update the prediction logic.
* Train a new model using your preferred machine learning algorithm.
* Save the trained model as model.joblib in the project directory.
* Update the loan_prediction.py file in the Express.js server code to reflect any changes made to the model.
* Restart the server to apply the changes.

# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please submit a pull request or open an issue.




