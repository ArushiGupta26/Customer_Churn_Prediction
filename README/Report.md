# Customer_Churn_Prediction
Customer Churn Prediction for a subscription based company

The dataset consists of:

100,000 rows

9 columns

Column names: 

 0   CustomerID                  100000 non-null  int64  
 
 1   Name                        100000 non-null  object
 
 2   Age                         100000 non-null  int64
 
 3   Gender                      100000 non-null  object
 
 4   Location                    100000 non-null  object
 
 5   Subscription_Length_Months  100000 non-null  int64
 
 6   Monthly_Bill                100000 non-null  float64

 7   Total_Usage_GB              100000 non-null  int64  
 
 8   Churn                       100000 non-null  int64 

 This was done as part of the internship evaluation assignment for SunbaseData for Machine Learning Internship.

 REPORT

Data Analysis: No Null Values Found (used isNull()), No outliers detected (Used Z Score), No significant correlation found between variables (heatmap), also used countplots, barplots, value_counts(), groupby to analyze data

Data Preprocessing: Dropped irrelevant columns: CustomerID AND Name, performed encoding on Gender and Location, split the data into training and testing data, performed scaling for the data to be fed into the models.

Model Selection: Trained 4 models: Random Forest, Decision Tree, Logistic Regression and an ANN Sequential model all resulting in poor accuracy (~50), however in all the metrics (precision, f1-score, recall and accuracy), Logistic Regression gave the best performance. Reason for poor accuracy could either be underfitting/ overfitriing of models or no underlying trend present in the data itself or the metric is not suitable for evaluation on this data itself.
 
 
