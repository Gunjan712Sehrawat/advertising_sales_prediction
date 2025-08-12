### Advertising Sales Prediction – Predicting sales from advertising spend using Multiple Linear Regression ###

### Purpose
This project demonstrates how advertising expenditures across TV, Radio, and Newspaper can be used to predict product sales through a Multiple Linear Regression model in Python.

### Importance
Enables businesses to forecast sales based on marketing budgets.

Helps optimize advertising strategies across different media channels.

Serves as a practical example of deploying regression models end-to-end.

### Dataset Used
Source: advertising_sales.csv (Kaggle) 
Features:
TV
Radio
Newspaper

***Target***: Sales

### Project Structure & Files
advertising_sales.ipynb: The main Colab notebook with data processing, modeling, and evaluation steps.

advertising_sales.csv: The dataset.

multiple_linear_regression_advertising.pkl: The serialized trained model. 


### Methodology
Data Loading & Exploration via Pandas.

Visual Analysis: Pairplots, scatter plots, or correlation checks. 

Model Training: Applied Multiple Linear Regression using TV, Radio, and Newspaper features.

### Model Performance:
***MAE*** : 1.275
***MSE***: 2.908
***RMSE*** : 1.705
***R²*** : 0.906

***Model Persistence***: Saved final model to a .pkl file for reuse. 


### How to Run Locally

git clone https://github.com/Gunjan712Sehrawat/advertising_sales_prediction.git
cd advertising_sales_prediction

# set up a virtual environment
pip install -r requirements.txt

# Open the notebook
colab notebook advertising_sales.ipynb
# Or run in Colab by uploading both notebook and CSV


### TV vs Sales  
![TV vs Sales](images/tv_vs_sales.png)

### Actual vs Predicted  
![Actual vs Predicted](images/actual_vs_predicted.png)


### Conclusion
The Multiple Linear Regression model effectively captures the relationship between advertising spend and sales. Results demonstrate meaningful predictive power, although performance may vary based on data distribution and feature relevance.

