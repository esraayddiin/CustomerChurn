# CustomerChurn

This project is aimed at analyzing customer churn data for a telecom company and predicting the likelihood of customers leaving. The dataset contains information on 7043 customers of a fictional telecom company operating in California.

## About the Dataset

Some variables in the dataset include:

- `CustomerID`: Customer ID
- `Gender`: Gender
- `SeniorCitizen`: Whether the customer is a senior citizen or not
- `Partner`: Whether the customer has a partner or not
- `Dependents`: Whether the customer has dependents or not
- `tenure`: Number of months the customer has stayed with the company
- `PhoneService`: Whether the customer has a phone service or not
- ...

## Libraries and Technologies Used

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- CatBoostClassifier (for modeling)

## Project Steps

1. Loading and initial inspection of the dataset
2. Data cleaning and preprocessing
3. Visualization and analysis of the dataset
4. Preparation of the dataset for modeling
5. Training the CatBoostClassifier model and calculating performance metrics
6. Determination and visualization of feature importance levels

## Results

- Compared to the base model, the final model has shown an increase in accuracy by 2%.
- The recall value has increased by 3%, indicating that the model better identifies churned customers.
- The precision value has increased by 3%, indicating an improvement in the model's ability to make correct predictions.

This project demonstrates how data science and machine learning techniques can be used for customer churn analysis and prediction.
