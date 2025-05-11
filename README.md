# House Price Prediction - Exploratory Data Analysis (EDA)
A simple EDA-based data science project analyzing house prices using Python ,Pandas and other tools .

# Summary :

This minor project focuses on performing Exploratory Data Analysis (EDA) on a house price dataset. The objective is to identify the key factors that influence housing prices using Python and common data science libraries. The project is designed as a beginner-friendly EDA task and includes data inspection, cleaning, visualization, and correlation analysis to uncover patterns and insights.

# Methods :

-> Data Collection: The dataset used was sourced from Kaggle and includes various features like price, number of bedrooms, bathrooms, square footage, and more.

->Data Cleaning: Handled missing values, checked for duplicates, and ensured correct data types.

Exploratory Data Analysis:
           -> Used descriptive statistics to understand distributions.
           -> Visualized relationships using bar plots, histograms, and scatter plots.
           -> Generated a heatmap to understand feature correlations with price.

-> Feature Analysis: Investigated the influence of features such as waterfront view, renovation status, and location on price.

-> Correlation Study: Identified features most strongly correlated with house price, such as sqft_living, grade, and bathrooms.

# Conclusion: 

This project demonstrated that certain features have a stronger impact on house prices than others. Key insights include:
            -> Square footage, number of bathrooms, and house grade are positively correlated with price.
            -> Waterfront properties and renovated homes tend to command higher prices.
            -> Some features like number of bedrooms showed weaker correlations than expected.

The project provides a solid foundation for building machine learning models in future work, and showcases the power of EDA in understanding and preparing data for predictive tasks.

## 📚 **Libraries Used**
- `pandas` for data manipulation
- `numpy` for numerical computations
- `matplotlib` and `seaborn` for data visualization
## 🚀 **How to Run**
1. Clone the repository:
    ```bash
    git clone https://github.com/Sunny9597/minor-project-house-price-analysis.git

    ```

2. Install the necessary libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the `eda.py` script to execute the data analysis:
    ```bash
    python eda.py
    ```

---

## 📢 **Author**
Sunny

---
## 📈 **Future Work**
- Explore machine learning models such as **Linear Regression** and **Random Forest** for predicting house prices.
- Perform **feature engineering** to create additional meaningful features.
- Implement **cross-validation** and **hyperparameter tuning** for better model performance.

---
## 📥 **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
