# Syria-Telecommunications

### Overview
The aim of this project is to leverage historical customer data to identify key factors influencing customer behavior with a focus on predicting customer churn. Churn refers to when customers stop or discontinue their relationship with a business or a service and for this case telecommunication services from Syria Tel.

### Data Understanding
The dataset given enables a comprehensive analysis of factors that may influence customer satisfaction, preferences and the likelihood of churn offering SyriaTel detailed recommendations to improve service offerings and mainatain their customer base.

### Objective
Build a classification model to predict whether a customer will churn or not churn providing insights to the company to reduce disatisfaction among customers and maintain their customer base.

### Data source 
https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset

### EDA 
Data was cleaned, analyzed, and categorical data was label-encoded.

 
 ### Modeling
There are three models used: a univariate model(Logistic Regression), a bivariate model(Decision Tree Model) and a multivariate model(Random Frest Model)

 #### Rndom Forest Model
Random Forest having the highest accuracy of90.8% and strong precision 87.67% along with a good recall of 71.3% was the most appropriate model for predicting churn. It provided the best balance between predicting churn and minimizing false positives.

<img width="347" alt="image" src="https://github.com/user-attachments/assets/161bdf2c-e0c1-4991-831e-1f19d45d0a53">

### Conclusion
From the analysis and model evaluatiion, Random Forest Model had the best predictions being multivariate and incluiding the key metrics of prediction.

### Next Steps
Integration of the Random Forest model into a customer relationship management system for real-time churn prediction for the different customer bases.
