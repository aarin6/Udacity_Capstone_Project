# Udacity_Capstone_Project

* Medium Story [Link](https://medium.com/@mansuri4638/starbucks-promotions-9b7a46621af6)

## Starbucks Capstone Challenge: Using Starbucks app user data to predict effective offers

## Project Overview
This is Udacity Nanodegree Data Science capstone project - Starbucks Capstone Challenge: How to predict effective offers using user data from the Starbucks App. The data is simulated data that mimics customer behavior on the Starbucks rewards mobile app. Not all users receive the same offer, and that is the challenge to solve with this data sets.

### 1. Installations
This project was written in Python, using Jupyter Notebook on Anaconda. The relevant Python packages for this project are as follows:

- pandas
- numpy
- json
- sklearn
- time
- matplotlib


### 2. Data Sets
The data is contained in three files:

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record
### 3. Results
The main results can be seen from the Notebook.

### 4. Licensing, Authors, Acknowledgements
The dataset is from Starbucks. The project orignates from Udacity course.

Data for coding project was provided by Udacity.
