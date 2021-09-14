# Udacity Data Scientist Nanodegree Capstone Project

# Starbucks-Capstone-Project

This is the readme file for the Udacity Data Scientist Nanodegree Capstone project.

## Project Overview :
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

Your task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

Every offer has a validity period before the offer expires. As an example, a BOGO offer might be valid for only 5 days. You'll see in the data set that informational offers have a validity period even though these ads are merely providing information about a product; for example, if an informational offer has 7 days of validity, you can assume the customer is feeling the influence of the offer for 7 days after receiving the advertisement.

You'll be given transactional data showing user purchases made on the app including the timestamp of purchase and the amount of money spent on a purchase. This transactional data also has a record for each offer that a user receives as well as a record for when a user actually views the offer. There are also records for when a user completes an offer.

Keep in mind as well that someone using the app might make a purchase through the app without having received an offer or seen an offer.

## Motivation :

### Case 1
Predicitng the type of offer (ie Bogo,discount,informational) based on the demographic attributes of the customer as well as company.

### Case 2
Predicting the purchase offer corresponding to which type of event like ‘offer received’, ‘offer viewed’, ‘transaction’ and  ‘offer completed’. This could  be achieved based on the demographic attributes of the customer and other attributes of the companies purchase offers given in the dataframes

## Libraries used
This project was written inipython notebook. The required Python packages for this project are as follows:

- numpy
- math
- pandas
- json
- matplotlib
- seaborn
- sklearn.model_selection (train_test_split module)
- sklearn.preprocessing (StandardScaler )
- sklearn.ensemble ( RandomForestClassifier,AdaBoostClassifier,ExtraTreesClassifier,BaggingClassifier)
- sklearn.metrics ( r2_score, mean_squared_error, mean_absolute_error,fbeta_score,accuracy_score)


## File Descriptions
This folder contains 4 files. 
- `Starbucks_Capstone_notebook.ipynb` : the code notebook .
- Capstone project results.pdf
- readme.md
-   `Data` :
    - 1. Profile.json
    - 2. Portfolio.json
    - 3. transcript.json :
