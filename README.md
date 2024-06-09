# Algerian Forest Fire Analysis

## Overview

This project involves the analysis of the Algerian forest fire dataset using various machine learning techniques. The main objective is to process and clean the dataset, generate visualizations, and derive insights by analyzing the Fire Weather Index (FWI). The project utilizes multiple linear regression, polynomial regression, and regularization models (Ridge and Lasso). Cross-validation and hyperparameter tuning are performed to evaluate model performance. The final model is saved and tested on unseen data.

## Dataset

The dataset contains various meteorological attributes that are potentially influential in the occurrence of forest fires. The attributes include:

- Day
- Month
- Year
- Temperature (°C)
- Relative Humidity (%)
- Wind Speed (km/h)
- Rain (mm/m²)
- Fine Fuel Moisture Code (FFMC)
- Duff Moisture Code (DMC)
- Drought Code (DC)
- Initial Spread Index (ISI)
- Buildup Index (BUI)
- Fire Weather Index (FWI)
- Classes (fire/not fire)
- Region

## Project Structure

├── data

│ ├── algerian_forest_fires_dataset.csv # Raw dataset

├── visualizations

  └── various_visualizations.png # Generated plots
  
│ ├── unseen_data.csv # Unseen data for testing

├── models

│ ├── linear_model.pkl # Saved Linear Regression model

│ ├── ridge_model.pkl # Saved Ridge Regression model

│ ├── lasso_model.pkl # Saved Lasso Regression model

├── README.md

└── .ipynb # Main script for data analysis and modeling



**Usage**
Data Preparation and Model Training
Run the .ipynb script to preprocess the data, train the models, and save the trained models:

## Visualizations
The script also generates various visualizations to understand the relationships between different features and the target variable (Classes). These plots will be saved in the visualizations directory.

Bar Plot of Fire Incidents by Month

Scatter Plot of Temperature vs. Fire Classes

## Results
The final model achieved the following performance on the test set:

Polynomial Regression (Degree 3) with Ridge Regularization (Alpha 0.1)
R^2 Score: 0.9697
RMSE: 0.9577
## License
This project is licensed under the MIT License.

## Acknowledgements
Dataset provided by the Algerian Government.
Analysis and modeling inspired by various machine learning resources and tutorials.
For any questions or suggestions, please feel free to contact me at yashsahu112000@gmail.com
    
