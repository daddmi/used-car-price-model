# Used Car Price Prediction

## Project Overview
This project builds a machine learning model to predict the selling price of used cars based on features like year, mileage, brand, fuel type, and transmission. It was developed as part of a data science assignment for an online car marketplace.

The goal is to provide an automated pricing tool that can help the marketplace set fair prices, attract sellers, and assist buyers in making informed decisions.

## Dataset
The dataset used is a car listings dataset provided by the course. It contains various attributes of used cars and their corresponding selling prices.

## Steps Taken
1. **Problem Understanding**  
   - Defined the business problem: accurate price estimation for used cars.  
   - Identified the target variable (`selling_price`) and feature columns.

2. **Data Exploration (EDA)**  
   - Checked missing values and data types.  
   - Computed summary statistics for numeric features.  
   - Visualized relationships between price and key features (scatter plots, box plots, correlation heatmap).

3. **Data Preprocessing**  
   - Handled missing values by imputing with median (numerical) and mode (categorical).  
   - Encoded categorical variables using one-hot encoding.  
   - Split data into training and testing sets (80/20).  
   - Applied feature scaling (standardization) to numeric features.

4. **Model Building**  
   - Trained a **Linear Regression** model as the baseline predictor.

5. **Model Evaluation**  
   - Evaluated on test data using:
     - **MAE (Mean Absolute Error)**
     - **RMSE (Root Mean Squared Error)**
     - **R² Score**
   - Interpreted results to understand prediction accuracy.

6. **Predictions**  
   - Made predictions for 5 sample cars to demonstrate the model in action.

7. **Insights**  
   - Identified which features most affect car prices (e.g., age, mileage, brand).  
   - Noted surprising patterns, such as non-linear relationships or unexpected feature importance.

## Repository Contents
- `wk2_project.ipynb` – Jupyter notebook with full analysis, code, and visualizations.
- `cleaned_car_data.csv` – The dataset after preprocessing (ready for modeling).
- `README.md` – This file.

## How to Run the Notebook
1. Clone or download this repository.
2. Open `wk2_project.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
3. Install the required packages if not already installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
