# Customer Relationship Prediction
In this project we are building a ML model to predict the propensity of customers to switch provider (churn), buy new products or services (appetency), or buy upgrades or add-ons proposed to them to make the sale more profitable

We have initially run a baseline model and Logistic regression model.

We’ve further built tree-based ensemble models - Random Forest, Gradient Boosting and XGBoost. Random Forest turned out to be the best model to predict Churn, Upselling and Appetency of customers. Selecting the top 25 features based on the permutance importance improved the performance of Random Forest model.

**Steps to run the notebook**

1) Please add the shortcut of this [drive folder](https://drive.google.com/drive/folders/12sa5znzETBehSbXSidr6LjA_WoU8JHWa?usp=sharing) on your drive before running the code .

2) Some of the cells take hours together to run, so to avoid that we've already done the processing and stored the relevant pickle files. Kindly load those files wherever required. This is also being added as a warning in our final notebook.

3) Final Notebook - [KDD cup 2009](https://github.com/akshaypt7/customer_relationship_prediction/blob/main/Kdd_cup_final_gradientboosting.ipynb)
