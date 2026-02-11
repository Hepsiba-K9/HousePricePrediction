House Price Prediction | Machine Learning
📌 Description

This project predicts house prices using Linear Regression based on key features such as area, number of bedrooms, and location. 
It helps understand how different factors influence property prices and demonstrates an end-to-end machine learning workflow.

🚀 Features

Predicts house prices using a trained Linear Regression model

Performs data preprocessing (cleaning, feature scaling, train–test split)

Evaluates model performance using MAE, MSE, and R² score

Visualizes data and predictions to analyze feature impact

🛠 Tech Stack

Frontend: HTML, CSS (for basic visualization / plots if applicable)

Backend: Python

Database: CSV dataset

ML / AI:

Linear Regression

Scikit-learn

Pandas, NumPy

Matplotlib / Seaborn

📂 Project Structure

house-price-prediction/
│── src/            # Source code (data preprocessing, training, evaluation)
│── public/         # Visualizations, plots, or static assets
│── models/         # Saved trained model files (.pkl or .joblib)
│── README.md       # Project documentation

Folder Details

src/ → Contains scripts for data cleaning, feature scaling, model training, and evaluation

public/ → Stores generated graphs and visualizations

models/ → Contains the trained Linear Regression model

README.md → Explains project details and usage

⚙️ How to Run the Project

Step 1: Clone the repository
git clone https://github.com/Hepsiba-K9/HousePricePrediction.git

Step 2: Navigate to the project directory
cd repo-name

Step 3: Install required libraries
pip install -r requirements.txt

Step 4: Run the project
python src/main.py

📊 Model Evaluation

The model is evaluated using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score

These metrics help measure prediction accuracy and model reliability.

📌 Future Improvements

Use Polynomial Regression or Decision Trees for non-linear patterns

Add more features such as amenities and proximity to landmarks

Deploy the model using Flask / FastAPI
