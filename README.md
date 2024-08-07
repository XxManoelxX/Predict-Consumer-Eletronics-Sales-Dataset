# PREDICT CONSUMER ELETRONICS SALES DATA SET



## Description:

This dataset provides insights into consumer electronics sales, featuring product categories, brands, prices, customer demographics, purchase behavior, and satisfaction metrics. It aims to analyze factors influencing purchase intent and customer satisfaction in the consumer electronics market.



### Observation:
The images are plotted using Plotly Express and then stored in a folder named "images" for better viewing on GitHub.


## Features:

   * ProductID: Unique identifier for each product.
   * ProductCategory: Category of the consumer electronics product (e.g., Smartphones, Laptops).
   * ProductBrand: Brand of the product (e.g., Apple, Samsung).
   * ProductPrice: Price of the product ($).
   * CustomerAge: Age of the customer.
   * CustomerGender: Gender of the customer (0 - Male, 1 - Female).
   * PurchaseFrequency: Average number of purchases per year.
   * CustomerSatisfaction: Customer satisfaction rating (1 - 5).
   * PurchaseIntent (Target Variable): Intent to purchase.

## Main Purpose of the Analysis
The analysis in this notebook aims to apply machine learning techniques to model and predict sales behavior. This can include tasks such as demand forecasting, customer segmentation, purchase pattern detection, and inventory optimization.

## Implications of the Analysis

1. **Demand Forecasting:** Predictive models can help estimate future sales based on historical patterns and exogenous variables, aiding in production and logistics planning.
2. **Customer Segmentation:** Clustering techniques can identify groups of customers with similar behaviors, allowing for more targeted marketing strategies.
3. **Inventory Optimization:** Accurate forecasts enable more efficient inventory management, reducing costs associated with overstocking or stockouts.
4. **Pattern Detection:** Exploratory analyses and association techniques can reveal hidden relationships in the data, such as frequently purchased together products, aiding in the creation of promotional campaigns.

## Methodology

### Exploratory Data Analysis (EDA)
EDA is a crucial step to understand the data distribution, detect outliers, and identify initial patterns. This can include:
- Descriptive statistics
- Visualizations of distributions and correlations
- Time series analysis

### Data Preprocessing
Preparing data for modeling involves:
- Data cleaning (handling missing values and outliers)
- Variable transformations (normalization, encoding categorical variables)
- Feature engineering (creating new variables from existing ones)

### Predictive Modeling
Applying machine learning algorithms, such as:
- Linear/multiple regression for sales forecasting
- Decision trees and random forests to capture non-linear relationships
- Neural networks to capture complex patterns and interactions

### Validation and Evaluation
Splitting data into training and testing sets to evaluate model performance using metrics such as:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Implementation
Implementing predictive models in decision support systems to automate real-time forecasts and optimizations.

## Conclusion
The analysis described in this notebook aims to provide valuable insights into sales behavior and apply advanced machine learning techniques to improve the operational and strategic efficiency of the company. The accuracy and robustness of predictive models can transform large volumes of data into practical and informed actions, creating competitive advantages in the market.



