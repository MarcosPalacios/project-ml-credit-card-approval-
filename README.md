![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Module 3 - Project 2 (ML) - Credit Card Approval


---


## Context ✏

Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.
 
Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations. Past models may lose their original predictive power. Logistic model is a common method for credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficients of each feature. In order to facilitate understanding and operation, the score card will multiply the logistic regression coefficient by a certain value (such as 100) and round it.
 
At present, with the development of machine learning algorithms. More predictive methods such as Boosting, Random Forest, and Support Vector Machines have been introduced into credit card scoring. However, these methods often do not have good transparency. It may be difficult to provide customers and regulators with a reason for rejection or acceptance.

More information can be found in Kaggle to understand the columns and the dataset structure: https://www.kaggle.com/rikdifos/credit-card-approval-prediction

---


## Project aim ✔

This project uses two datasets containing applicant data and credit approval data, with the aim to determine which clients are *good* or *bad* based on historical credit data, as well as creating a machine learning model than can reliably classify new customers into each categories. Some techique, such as vintage analysis is recommended to construct the label. Also, the data is unbalanced and is real issue in this task. The definition of 'good' or 'bad' is not given and must be defined.

---


## Setup & environment ⚙

This project has been created and run using **Python 3.8.8**. It must be kept in mind that some of the needed ML libraries are changing on a regular basis, and some of those changes might eventually break some of the code.

All necessary libraries are included in the *credit-approval* notebook. 


---


## Internal structure 📚

The project is structured into the following sections:

1. Data exploration.
2. Data cleaning.
3. Data wrangling.
4. PCA.
5. Data normalization & oversampling.
6. Pipeline and model creation.
7. Model evaluation.
8. Model optimization.


---


## Notes and warnings ⁉

This notebook uses many machine learning libraries which are in constant evolution, and this fact might at some point break the code of certain sections. Copy & paste is therefore allowed, but not encouraged if you want to replicate the same results.

---
