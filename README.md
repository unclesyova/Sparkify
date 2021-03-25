# Sparkify
In this project I made an attempt to predict users who are about to cancel music streaming service  
based on available statistics: number of songs listened per day, rate of errors occurances,   
how many songs were listened before logging out and more.  
The problem is directly related to classification problem.  

### Motivation  
The problem of keeping users satisfied is relevant to any kind of service, as it   
contribute to a positive overall image of the service, helps to keep service's audience and attract new  
users, which would resault in higher profits.   

### List of files
* Sparkify.ipyb - The source code.  
* small_sparkify-event-data.json - The dataset containing the informations about user activities.  

### How to use
- download the dataset and the source code file.  
- open in jupyter notebook and run.  
- some changes may needed to be made depending on the environment, because the project uses Spark in local mode.  

### 3rd party libraries
The project uses pandas and matplotlib for data visualization.  
Pyspark.sql and pyspark.ml libraries are used for wrangling the data end building ML models.  

### Summary of the results  
During the project the following steps were made:
1. Data was downloaded and analyzed.
2. Data was preprocessed and reshapen, suitable features were designed.
3. ML model was built and trained.
4. The results were tested and assessed with f1 score metric.
5. The final result was deployed on IBM cloud with a larger dataset.  
  
The final results are 0.65 for the small dataset and 0.57 for a larger dataset deployed on IBM cloud.  
Source code is scalable and suitable to analyze different datasets.

### License
This code is under APACHE LICENSE 2.0

### Author & Acknowledgements
Author: Zeev Peisakhovitch  
Much of the usefull information was taken from this [article](https://neptune.ai/blog/tabular-data-binary-classification-tips-and-tricks-from-5-kaggle-competitions)
