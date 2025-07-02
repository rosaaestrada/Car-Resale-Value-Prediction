# Car Resale Value: Prediction & Key Influencing Factors

## Purpose
This project explores whether the resale value of a car can be accurately predicted using features like brand, age, mileage, fuel type, and more, while also uncovering which attributes contribute most to price depreciation.

## Questions Answered:
- Can we predict the optimal selling price of a car?
- What factors influence resale value?
- Which brands hold their value best?
- Do automatic cars depreciate faster than manual ones?
- Does high mileage equal lower price?

## Kaggle Notebook

## Data Source:
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)


## Files:
- **Data** - Contains raw data, preprocessed data, and the location where the data was collected
- **Jupyter Notebook** - The full source code along with explanations as a .ipynb file
- **Python Code** - The full source code along with explanations as a .py file
- **Results** - Summary Statistics, Visualizations, and Final Evaluation of the project

## Built with:
- Python= 3.12.3

## Tools/Libraries used:
- Pandas= 2.2.2
- NumPy= 1.26.4
- Matplotlib= 3.9.2
- Seaborn= 0.13.2
- Scikit-learn= 1.5.1
- XGBoost= 3.0.2

## Summary Statistics

## Actual vs. Predicted Car Prices (Random Forest Model)

##Summary of Key Insights:
- 🔧 Present price, car age, and brand are the strongest predictors of resale value.
- 📉 Automatic cars depreciate faster than manual ones, losing more value on average.
- 🚗 High mileage has little predictive power on resale price in this dataset (correlation ≈ 0.03).
- 🏆 Random Forest outperformed Linear Regression and XGBoost, achieving the highest accuracy (R² = 0.72).
- 💰 Brands like Vitara Brezza and Bajaj Avenger retained over 90% of their original price, signaling strong demand and low depreciation.
