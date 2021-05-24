# Udacity - Starbucks Capstone Challenge

```
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

- Install a recent version of python anaconda distribution
- Clone the repository and run the jupyter notebook

The jupyter notebook is supposed to work with python3. The following 3rd party libs are used:
- pandas
- numpy
- sklearn
- matplotlib
- scipy
- seaborn

## Project Motivation<a name="motivation"></a>
This project is the capstone probject of my Udacity Data Science nanodegree. In this project, the data sets about Starbucks transactions provided by Udacity/Starbucks are analyzed. The data sets contain information about transactions and if a customer uses BOGO (buy one get one free) or discounts at his/her transaction. The data is preprocessed and then employed in machine learning models where we finally predict if a customer is keen to an offer (bogo, discount). The following three questions are to be answered by this notebook:

- What are the persona cluster among the customers in the data set?
- Can we in general predict if a customer takes an offer and to which offer (bogo or discount) he/she is more responsive?
- Which characteristica do have the most common influence on the prediction?

In order to analyze and evaluate the data we are employing the CRISP-DM process:

- Business Understanding - we have raised the three key questions above about the Starbucks data set
- Data Understanding - we have explored the three test sets provided by Starbucks/Udacity
- Data Preparation - we have cleaned the data by dropping features, by imputing values, and by converting categorical into numerical data from the original data set
- Modelling - we have modelled the classification and prediction questions with a KMeans classifier and a random forest classifier 
- Evaluation - we have evaluated the resuling models. For the KMeans classifier, we have used the Silhouette score, for the random forest classifier, we have used the accuracy score
- Deployment - we have discussed the findings as a final report in a medium blog post [here](https://dominiksieber.medium.com/how-effective-are-starbucks-app-offers-6f7b13dd5f36).

## File Descriptions <a name="files"></a>

The  jupyter notebooks `starbucks_capstone_notebook.ipynb` is available here in this repo to illustrate the required steps which were necessary to analyse the available data and to finally answer the above questions. 

The notebook also contains the function that generates the final model which is used to categorize the customers into persona clusters and to predict whether a customer is reponsive to an offer or not.

The data can be foudn under the subfolder `data`. All images created by the jupyter notebook can be found under the subfolder `images`.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://dominiksieber.medium.com/how-effective-are-starbucks-app-offers-6f7b13dd5f36).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The data was provided by Udacity. Feel free to use the code here as you like.
```
