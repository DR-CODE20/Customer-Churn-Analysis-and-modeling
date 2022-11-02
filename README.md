# Customer-Churn-Analysis-and-modeling
# Problem Statement: 
* Recommend the steps to retain existing telecom customers. In the industry retaining customers is becoming a big challenge on a day by day cases and acquiring new customers is even draining, hence so retaining the existing customers is highly paramount than acquiring new customers.
* Know the customer's behavior and recommend the steps to retain existing customers and build a model to predicts the possibility that an existing customers may leave.
    1. Recommend the steps to retain existing telecom customers.
    2. Build customer churn, prediction model.

# Analysis Procedure
1. Imports Libraries
2. Data Info 
3. Customer Analysis
    1. Customer segmentation
    2. Steps to retain customers
4. Machine Learning Model 
    1. Random Under-Sampling
    2. EDA
    3. Feature Scaling 
    4. Decision Tree | Confusion matrix, Classification Report
    5. Random Forest | Confusion matrix, Classification Report
    6. Gradient Boost | Confusion matrix, Classification Report
    7. KNN | Confusion matrix, Classification Report
5. Evaluation AUC ROC Curve for all models 
6. Conclusion

# Dataset Link
The public dataset was used for this analysis and was gotten from data.world website, created by Bob-Wakefield
* Link: data.world/bob-wakefield/call-center-data
* size: 1.32Mb
* Format: CSV

# DESCRIPTION
* Anonymized Telecom Customer Data

# SUMMARY
* This dataset contains information about the customers of a telecom. While there are a number of analysis you can perform with this dataset, it does include rather or not the customer churned so it is useful to lear how to do customer churn.


# Data Dictionary
| Column | Feature Type | Description |
| :---- | ---- | ---- |
| recordid | integer | Primary key of the record |
| state	| string | Customers state. |
| account_length |integer | Age of account in months. |
| area_code | string | Area code. |
| international_plan | boolean | Rather or not the customer has an international calling plan. |
| voice_mail_plan | boolean | Rather or not the customer has a voice mail plan.|
| number_vmail_messages | integer | Number of VM messages customer currently has on the server. |
| total_day_minutes | decimal | Customers total usage of day minutes in plan. |
| total_day_calls | integer | Total number of calls customer has made during the day. |
| total_day_charge | decimal | How much the customer has been charged for day minutes. |
| total_eve_minutes	| decimal | Customers total usage of evening minutes in plan. |
| total_eve_calls | integer | Total number of calls customer has made during the evening. |
| total_eve_charge | decimal | How much the customer has been charged for evening minutes. |
| total_night_minutes | decimal | Customers total usage of night minutes in plan. |
| total_night_calls | integer | Total number of calls customer has made during the night. |
| total_night_charge | decimal | How much the customer has been charged for night minutes. |
| total_intl_minutes| decimal | Total international minutes. |
| total_intl_calls | integer | Total international calls.|
| total_intl_charge | decimal | Total international charges. |
| number_customer_service_calls | integer | How many times the customer has called the IVR system. |
| churn | boolean | Customer has churned. |
| customer_id | string | Enterprise ID of the customer. |
