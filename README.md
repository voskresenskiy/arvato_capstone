# arvato_capstone
The script with the analysis done for the capstone project in the framework of Udacity Data Scientis Nanodegree

## Goals of the project

The project included three main challenges:

- Using the data of Arvato and data with demographics on the German population and employing the methods of unsupervised learning, I needed to identify the segments of Arvato customersâ€™ database and describe which parts of the German population are well represented in the Aravato dataset and which parts are underrepresented.
- I needed to make a classification model that would predict which customers would respond to the mailout campaign launched by Arvato.
- Finally, I was expected to submit my predictions to the Kaggle and compete with other students of Udacity.

## Results of the project

Unsupervised learning approach (combining PCA and K-Means) allowed me to identify the segments of Arvato's customers and compare the charasteristics of the customers with German population data. 

In the step with the prediction, the Gradient Boosting algorithm gave me the best result and was chosen for the Kaggle competition. The AUC score of the final model readched the score of 0.796 in the Kaggle leaderboard. 
    
 ## File description
 
The Jupyter notebook includes all the main steps of the analysis with my comments. 
The more detailed description of the analysis can be found in this [Medium blogpost](https://medium.com/@vadimvoskresensky/customer-segmentation-and-classification-for-arvato-financial-services-30568b3e8b9c)

## Libraries

To successfully reproduce my script on your machine, the following packages should be installed: pandas, nltk, numpy, sklearn, imblearn, seaborn, tqdm, lightgbm
