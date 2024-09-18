# Wind Turbine Power Prediction

This project involves predicting the power generation capacity of wind turbines using various features such as rotor diameter, hub height, manufacturer, and turbine model. The project follows a structured data science process, including data cleaning, exploratory data analysis, and model building using the `tidymodels` package in R.

## Project Overview
The goal of this project is to develop a machine learning model to predict turbine power (in kW) based on its characteristics. We analyze data from various wind turbines in Canada, focusing on factors such as geographical location, design features, and manufacturers.

### Key Steps:
1. **Data Preprocessing**:
   - Cleaned missing data and removed irrelevant columns such as `notes`.
   - Handled missing values in columns like `turbine_rated_capacity_k_w` and `rotor_diameter_m`.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized the distribution of turbine power across various provinces.
   - Investigated relationships between rotor diameter, hub height, and power output.
3. **Modeling**:
   - Trained a random forest model using the `tidymodels` package to predict turbine power based on design features.
   - Evaluated the model using metrics like RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and R-squared.
4. **Predictive Insights**:
   - The model achieved an R-squared of 0.98 on the test data, indicating high accuracy in predicting turbine power.

## Dataset
- **Source**: The wind turbine data was sourced from the TidyTuesday project.
- **Size**: The dataset contains 6,477 records of wind turbines with 14 variables, including rotor diameter, hub height, and rated capacity.

## Libraries Used:
- `tidyverse`
- `tidymodels`
- `ggplot2`
- `janitor`
- `skimr`

## How to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wind-turbine-power-prediction.git
