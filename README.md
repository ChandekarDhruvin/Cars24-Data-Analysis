# Car Price Prediction Project

This repository contains the implementation of a Car Price Prediction Model using machine learning techniques to predict car selling prices based on various features such as car type, mileage, engine size, and other related attributes. The model uses linear regression for both univariate and multivariate analysis and evaluates model performance based on various metrics.

## Table of Contents
- Overview
- Data Analysis
- Feature Engineering
- Modeling
- Results
- Technologies Used
- Setup
- License

## Overview
The goal of this project is to predict the selling price of a car based on various attributes provided in the dataset. This dataset includes columns such as mileage, engine size, km driven, fuel type, seller type, and other car features.

The project performs Exploratory Data Analysis (EDA), handles missing or incorrect data, performs feature engineering, scales the data, and applies machine learning models for prediction. The evaluation of the model is done using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-Squared (R²).

## Data Analysis

### Initial Exploration:
- Dataset shape, types of columns, and basic descriptive statistics were reviewed.
- Distribution of features like selling_price, mileage, km_driven, engine, etc. were visualized.

### Cleaning Data:
- Cars with mileage equal to 0 were removed.
- Removed rows with extreme km_driven values (e.g., the highest mileage recorded).
- Handled categorical columns such as fuel_type, seller_type, transmission_type, and seats.

### Visualizations:
- Histogram and box plots were used to visualize the distribution of selling_price, mileage, engine size, etc.
- Log transformation was applied to selling_price for better visualization.
- Correlation matrix and pairplots were used to understand relationships between features.

## Feature Engineering
- Extracted the make (car brand) and model from the full_name column to use them as separate features.
- One-hot encoded categorical features such as fuel_type, transmission_type, and seller_type.
- Created new binary columns based on seats (i.e., <=5 and >5).
- Normalized the data using MinMaxScaler to scale numeric columns to a range between 0 and 1.

## Modeling

### Univariate Analysis
- Initially, a linear regression model was trained using a single feature (model) to predict the selling_price.

### Multivariate Analysis
- A multiple linear regression model was built using all features to predict the selling_price.
- The importance of each feature was assessed based on the coefficients of the linear regression model.
- The model’s performance was evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-Squared (R²).

## Results
- **R-Squared (R²)**: 0.95, indicating that the model explains 95% of the variance in the selling price.
- Mean Squared Error (MSE) and Mean Absolute Error (MAE) suggest room for improvement in model performance.
- Feature importance revealed that certain columns have a higher impact on the price prediction than others.

## Technologies Used
- **Python**
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Data Processing & Visualization**: Pandas for data handling, Seaborn and Matplotlib for data visualization.
- **Machine Learning**: Scikit-learn for Linear Regression and model evaluation.

## Setup
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place your dataset (e.g., cars24-car-price.csv) in the project directory.

4. Run the analysis:
   ```bash
   python car_price_prediction.py
   ```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

![download](https://github.com/user-attachments/assets/a906dd23-c05b-4d5f-bc50-525d8ce6d0d9)
![image](https://github.com/user-attachments/assets/a72f2a09-8804-437b-a01e-018b1184c718)

# Name :Chandekar Dhruvin

**Email : dhruvinchandekar@gmail.com**
**Linkedin : www.linkedin.com/in/chandekar-dhruvin**

**Portfolio :- https://www.datascienceportfol.io/Dhruvin**

# Projects

**1. Banglore Price Prediction :- https://github.com/ChandekarDhruvin/BanglorePricePrediction**

**2. Amazon Sales Analysis :- https://github.com/ChandekarDhruvin/Amazon_Sales_Analysis**

**3. Retail Store Data :- https://github.com/ChandekarDhruvin/OIBSIP_Task01-RetailStoreData**

**4. House Price Prediction :- https://github.com/ChandekarDhruvin/OIBSIP_Task03-House_Price_Prediction**

**5. ECommerce Purchase :- https://github.com/ChandekarDhruvin/ECommerce-Purchase**

**6. Wine Quality Prediction :- https://github.com/ChandekarDhruvin/OIBSIP_Task04-WineQuality_Prediction**

**7. New York AirBNB Data Analysis :- https://github.com/ChandekarDhruvin/OIBSIP_Task02-NewYork_AirBnb_Data_Analysis**

**8. AdultData Analysis :- https://github.com/ChandekarDhruvin/AdultDataSet_analysis**

**9. Diwali Sales Data Analysis :- https://github.com/ChandekarDhruvin/Diwali-Sales-Data-Analysis**



