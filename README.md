# CCE Data Analysis
 This project, conducted under the Center of Community Energy (CCE), aims to investigate the opinions of the San Diego community regarding e-bikes. The objective is to provide recommendations to San Diego County regarding the development of regulations related to e-bikes.
 The documents stored in this repository illustrate the methodology we employed to analyze survey data gathered both from the San Diego community and online sources. The analysis process mainly consists of four parts:
 
 __Step 1 : Survey Data Cleaning__
 - In this phase, we loaded 3 raw survey data files into JupyterNote Book. Each response is cleaned for easier future analysis.

 __Step 2 : SD Zipcode Clustering__
 - In this phase, we adopted unsupervised k-means clustering to divide San Diego county into smaller groups of similar demographic characters.
 
 __Step 3 : Survey Data Labeling__
 - In this phase, we assigned cluster labels obtained in step 2 to our own survey data.
 - In this file contains a file "Survey Data Visualization by Clusters", which stores visualizations depicting the distribution of survey question counts across communities with various labels.
 
 __Step 4 : Survey Data Normalization__
 - In this phase, we normalized our survey data by community size.
 - In this file contains a file "Normalized Survey Data Visualization", which stores visual representations of survey data that have been adjusted for the population size of each labeled community.
 
