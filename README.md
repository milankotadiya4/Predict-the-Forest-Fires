# Forest Fire Prediction

## Project Overview
This project aims to predict the burned area of forest fires in the northeast region of Portugal using various meteorological and other relevant data. The project compares the performance of three regression models: Random Forest Regressor, Neural Network, and Linear Regression.

## Dataset
The dataset used in this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/forest+fires). It includes the following features:
- Spatial coordinates (X, Y)
- Temporal features (Month, Day)
- Fire weather indices (FFMC, DMC, DC, ISI)
- Meteorological data (Temperature, RH, Wind, Rain)
- Target variable: Burned area (in hectares)

## Project Structure
1. **Data Import and Preprocessing**:
   - Loading packages and data
   - Data exploration, cleaning, and preprocessing
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing data relationships
3. **Model Training and Evaluation**:
   - Implementing Random Forest Regressor, Neural Network, and Linear Regression
   - Evaluating models using MSE, MAE, and R-squared metrics

## Installation and Usage
To run the project, ensure you have the following packages installed:
- numpy
- pandas
- seaborn
- scikit-learn
- matplotlib

You can install these packages using pip:
```bash
pip install numpy pandas seaborn scikit-learn matplotlib
