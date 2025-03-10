# Student-Perform-Prediction
Student Performance Prediction

Overview

This project predicts student exam scores based on study hours and other influencing factors such as previous scores and participation in extracurricular activities. It uses a Linear Regression model to analyze and visualize the relationship between these factors and the final exam scores.

Features

* Generates a synthetic dataset with:

* Study hours

* Previous exam scores

* Extracurricular activities involvement
  
* Exam scores as the target variable

* Performs exploratory data analysis (EDA) using Seaborn and Matplotlib.

* Splits the data into training and testing sets.

* Trains a Linear Regression model using Scikit-learn.

* Evaluates model performance using MAE, MSE, and RMSE.

* Visualizes actual vs. predicted scores.

Installation

Ensure you have Python installed along with the necessary libraries. Install dependencies using:

pip install numpy pandas scikit-learn matplotlib seaborn

Usage

Run the Python script to train the model and visualize the results:

python student_performance.py

Output

* A scatter plot showing the correlation between study hours, previous scores, and exam performance.

* Model evaluation metrics (MAE, MSE, RMSE) printed in the console.

* A scatter plot comparing actual vs. predicted scores.

Future Improvements

* Include additional factors like attendance and assignment scores.

* Use more advanced models such as Random Forest or Neural Networks.

* Implement a user interface for real-time predictions.

License

This project is open-source and free to use for educational purposes.

