Introduction about this dataset

Digital payments are evolving, but so are cybercriminals.
According to the Data Breach Index, more than 5 million records are being stolen on a daily basis, a concerning statistic that shows - fraud is still very common both for Card-Present and Card-not-present types of payments.
In today’s digital world where trillions of Card transaction happens per day, detection of fraud is challenging.


Feature Explanation:

distance_from_home: the distance from the home where the transaction happened.

distance_from_last_transaction: the distance from the last transaction that happened.

ratio_to_median_purchase_price: Ratio of purchased price transaction to median purchase price.

repeat_retailer: Does the transaction happen from the same retailer?

used_chip: Is the transaction through a chip (credit card).

used_pin_number: This is the transaction that happened by using a PIN number.

online_order: Is the transaction an online order?

fraud: Is the transaction fraudulent?


Project Objectives:

Problem Statement

Loading and inspecting the data

Data Cleansing

Data Correlation

Exploratory Data Analysis (EDA)

Data Pre-processing

Model building

Model Evaluation

Model Testing

Note:
In the case of credit card fraud detection, we want to avoid false negatives as much as possible. Fraud transactions cost us a lot and thus we want to take appropriate measures to prevent them. A false negative case means that a fraud-positive transaction is assessed as a genuine transaction, which is detrimental.
