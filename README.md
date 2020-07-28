# Bank Marketing Campaign
<p align="center">
  <a href="https://www.youracclaim.com/badges/a78eec88-8a69-43fb-8d1a-c0afe6cf2233/public_url" rel="Badge"><img src="https://i.imgur.com/8at4RP2.png"></a>
  <a href="https://coursera.org/share/6cf953584607f1958e76b02bf9d0355e" rel="Certificado"><img src="https://i.imgur.com/azNfrak.png"></a>  
</p>

## Improving Return Rate from Marketing Calls
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT) [![Version: Python](https://img.shields.io/badge/Python-3.6.0-blue)](https://www.python.org/downloads/) 

This project creates a ML model to improve the return rate from a bank campaign. 
The Bank of Portugal makes its campaigns by calling clients and asking if they want to open a term deposit. The return is a 'yes' or 'no'. The goal of the model is to select clients most likely to say yes, reducing the number of calls and increasing the ratio call/yes. 

## Technologies :rocket: :

  * Language:
    * [Python 3.6](https://www.python.org/)
  * Data Manipulation:
    * [Pandas](https://pandas.pydata.org/)
    * [NumPy](https://numpy.org/)
  * Data visualization:
    * [matplotlib](https://matplotlib.org/)
    * [SeaBorn](https://seaborn.pydata.org/)
  * Machine Learning Library:
    * [ScikitLearn](scikit-learn.org/)
  * Production Enviroment:
    * [IBM Watson Studio](https://www.ibm.com/br-pt/cloud/watson-studio)
 

## Project Tree
### Main Folder
Has Documentation and presentation for both Stakeholders and Data Scientists.
### Graphs
Has main plots used in the presentations.
### Notebooks
Has the code divided in 4 steps:
  1. ETL and Data Analysis
  2. Model Definition
  3. Model Training and Feature Re-Enginieering
  4. Results and Model Deployment

# Results
Using the ML model we reduced the number of calls made (using test dataset) by 88%. The return from calls increased from 11% to 52%. 

## Final Product
As a result from this work, we got a model deployed to IBM Watson Studio. It allows us to make predictions using a RESTFUL API using json notation.

# Future Versions
We had an insight while working with the data. We found out that people open more accounts when economic indicators are good. As future work, we can train an LSTM, or similar model to predict economic indexes. It will allow the model to predict not just who, but also when to call.

**Made by Iury Melo**