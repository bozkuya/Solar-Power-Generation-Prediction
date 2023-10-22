# Solar Power Generation Prediction

This repository contains a project where machine learning models are utilized to predict the power output of a solar farm based on weather conditions and previous generation data.

## Dataset

The dataset consists of generation data and weather data from a solar farm. The generation data includes features like DC Power, AC Power, Daily Yield, and Total Yield. The weather data includes features like Ambient Temperature, Module Temperature, and Irradiation.

- `Plant_2_Generation_Data.csv`: Contains the power generation data of the solar farm.
- `Plant_2_Weather_Sensor_Data.csv`: Contains the weather data recorded at the solar farm.

## Data Preprocessing and Exploration

The data is cleaned, preprocessed, and explored using various visualization techniques. The generation data and weather data are merged, and feature distributions and correlations are analyzed. Time series trends for key features are also visualized.

## Machine Learning Models

Various machine learning models including K-Nearest Neighbors (KNN), Decision Trees, Gradient Boosting, and ensemble techniques are employed to predict the AC Power output of the solar farm based on features like Daily Yield, Total Yield, Ambient Temperature, and Irradiation.

## Model Evaluation and Improvement

The performance of the models is evaluated and improvements are made through hyperparameter tuning, feature scaling, and cross-validation.

## Libraries Used

- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for building and evaluating machine learning models

## How to Run

1. Clone the repository to your local machine.
2. Ensure that you have all the necessary libraries installed.
3. Run the Jupyter Notebook to see the data visualization, model building, and evaluation steps.

## Visualizations

Various visualizations like histograms, scatter plots, and time series plots are used to understand the data distribution and trends.

## Results

The models are evaluated and their performance is displayed in the notebook. You can tune the models further to achieve better accuracy.

## Future Work

- Incorporating more features and data for training the models.
- Exploring deep learning approaches for prediction.
- Developing a deployable solution for real-time predictions.

## Contribution

Feel free to fork the project, make improvements or fix bugs and send a pull request.
