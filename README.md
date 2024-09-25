EV Power Prediction


This project focuses on predicting the power consumption of Electric Vehicles (EVs) based on historical data. The analysis leverages various machine learning algorithms to understand and model the energy requirements of EVs under different conditions. The notebook demonstrates data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

Key objectives:
Analyze EV power consumption patterns.
Train machine learning models to predict power usage.
Evaluate model performance and optimize prediction accuracy.
Data
The data used in this project comes from EV_Cars_India_2023 (kaggle.com). It includes the following variables:

Timestamp: Time of measurement
EV Power Usage: Actual power usage of the vehicle
Other Variables: Additional features (speed, battery state)

Models Used
Several machine learning algorithms are applied in the notebook, including:

Linear Regression
Decision Trees
Random Forests
Gradient Boosting
Support Vector Machines (SVM)
The models are evaluated based on standard metrics such as RMSE (Root Mean Square Error) and MAE (Mean Absolute Error).

Dependencies
To run this project, you will need the following libraries:

Python 3.x
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook
Install the dependencies using:

bash
Copy code
pip install -r requirements.txt
How to Run the Code
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/EV_Power_Prediction.git
Navigate to the project directory:
bash
Copy code
cd EV_Power_Prediction
Open the Jupyter Notebook:
bash
Copy code
jupyter notebook EV_Power_Prediction.ipynb
Run all the cells in the notebook to train and evaluate the models.
Results
The models produce predictions of EV power consumption. Based on the evaluation metrics, the best model can be selected for deployment in an actual EV power management system.
