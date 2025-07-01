✈ Flight Price Prediction

This repository contains a machine learning project focused on predicting flight ticket prices based on various features such as departure time, arrival time, airline, source, destination, and duration.




📌 Project Overview :

Flight price prediction is a useful application of machine learning that helps travelers and businesses estimate the cost of air travel based on multiple variables. In this project:

The dataset is preprocessed and cleaned.

Categorical variables are encoded.

Feature engineering is applied to extract meaningful information.

Multiple regression models are trained to predict flight prices.

Model performance is evaluated using metrics such as R² Score and RMSE.





🗂 Dataset

The dataset used in this project includes the following features:

Airline

Source

Destination

Date of Journey

Departure and Arrival Time

Duration

Total Stops

Price (Target Variable)


> Note: The dataset was imported from a CSV file. It has undergone cleaning and transformation steps in the notebook.






📊 Exploratory Data Analysis (EDA) 

Distribution of price with respect to airline and stops.

Visualizations using seaborn and matplotlib.

Feature importance analysis using tree-based models.





🧠 Model Building

The following models were trained and compared:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

XGBoost Regressor


Random Forest and XGBoost gave the best results with high accuracy and low error.





🏁 Final Model

The best-performing model (Random Forest) was serialized using pickle for deployment purposes.

Input features are selected based on feature importance.

A prediction function is provided to take user input and return the predicted price.





🧪 Evaluation Metrics

R² Score

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)





📦 Requirements

To run this project, install the following packages:

pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
pickle




🚀 How to Use

1. Clone the repository


2. Install dependencies


3. Run the Jupyter Notebook: Flight_Price_Prediction.ipynb


4. Train the model and test the predictions


5. Use the saved model (model.pkl) to deploy in a web app or API






📁 File Structure

📦Flight_Price_Prediction
 ┣ 📜Flight_Price_Prediction.ipynb
 ┣ 📜model.pkl
 ┗ 📜README.md




🙌 Acknowledgements

Dataset sourced from Kaggle

Inspired by real-world airline ticket pricing systems.
