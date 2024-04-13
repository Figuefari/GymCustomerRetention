## Proyect description

A chain of gyms needs to prevent customer churn. We worked with the chain's data to predict the probability of churn for each customer using data prediction tools.

## Tasks

1. Preprocess the data.
2. Perform exploratory data analysis (EDA).
   - Study average values and standard deviation.
   - Observe groups of people who canceled and those who stayed.
   - Plot histograms and feature distributions.
   - Create a correlation matrix.
3. Build a binary classification model to predict user cancellations.
   - Data splitting.
   - Model training.
   - Evaluate accuracy, precision, and recall for each model.
4. Create user clusters.
   - Standardize data.
   - Create a distance matrix.
   - Train the clustering model.
   - Observe cluster values and calculate cancellation rates for each one.
5. Conclusions and recommendations.

## Data description

The dataset includes the following fields:

- 'Churn' — cancellation for the current month
- 'gender'.
- 'Near_Location' — whether the user lives or works in the neighborhood where the gym is located.
- 'Partner' — whether the user works at a partner company (the gym has partner companies whose employees get discounts; in those cases, the gym stores information about the clients' employers).
- 'Promo_friends' — whether the user originally signed up through a "bring a friend" offer (used a friend's promotional code when they paid the first subscription).
- 'Phone' — whether the user provided their phone number.
- 'Age'.
- 'Lifetime' — the time (in months) since the user first came to the gym.

Visit and purchase log data and data on the current membership status:
- 'Contract_period' — 1 month, 3 months, 6 months, or 1 year.
- 'Month_to_end_contract' — the number of months left until the contract expires.
- 'Group_visits' — whether the user participates in group sessions.
- 'Avg_class_frequency_total' — average frequency of visits per week over the customer's lifetime.
- 'Avg_class_frequency_current_month' — average frequency of visits per week during the current month.
- 'Avg_additional_charges_total' — total amount of money spent on other gym services: cafeteria, sports products, cosmetics, massages, etc.

## Tasks

1. Preprocess the data.
2. Perform exploratory data analysis (EDA).
   - Study average values and standard deviation.
   - Observe groups of people who canceled and those who stayed.
   - Plot histograms and feature distributions.
   - Create a correlation matrix.
3. Build a binary classification model to predict user cancellations.
   - Data splitting.
   - Model training.
   - Evaluate accuracy, precision, and recall for each model.
4. Create user clusters.
   - Standardize data.
   - Create a distance matrix.
   - Train the clustering model.
   - Observe cluster values and calculate cancellation rates for each one.
5. Conclusions and recommendations.

## Table of Contents

 1. Exploratory Data Analysis:
    - Initialization
    - Data Loading
    - Data Quality Assessment
    
2. Data Preprocessing:
    - Data Standardization
 
 3. Model Construction:
    - Model Training
    - Metrics Evaluation

4. User Clusters  
    - Dendrogram
    - K-means Clustering
 
5. Conclusions and Recommendations

## Used libraries

- pandas
- matplotlib
- seaborn
- plotly
- sklearn
