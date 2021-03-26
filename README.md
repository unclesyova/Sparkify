# Sparkify
In this project, I made an attempt to predict the users who are about to cancel a music streaming service  
based on the available statistics: the number of songs listened per day, the rate of errors occurances,   
the number of songs that were listened to before logging out and more.  
The problem is directly related to the classification problem.  

### Motivation  
The problem of keeping users satisfied is relevant to any kind of service, as it   
contributes to a positive overall image of the service, helps to keep service's audience and attract new  
users, which would result in higher profits.   

### List of files
* Sparkify.ipyb - The source code.  
* small_sparkify-event-data.json - The dataset containing the information about the user activities.  

### How to use
- download the dataset and the source code file.  
- open it in jupyter notebook and run.  
- some changes may need to be made depending on the environment because the project uses Spark in local mode.  

### 3rd party libraries
The project uses pandas and matplotlib for data visualization.  
Pyspark.sql and pyspark.ml libraries are used for wrangling the data and building ML models.  

### Summary of the results  
During the project the following steps were made:
1. Data was downloaded and analyzed.
2. Data was preprocessed and reshapen, suitable features were designed.
3. ML model was built and trained.
4. The results were tested and assessed with the f1 score metric. 
  
The final results are 0.63 for the small dataset.  
Source code is scalable and suitable to analyze different datasets.

### License
This code is under APACHE LICENSE 2.0

### Author & Acknowledgements
Author: Zeev Peisakhovitch  
Much of the usefull information was taken from this [article](https://neptune.ai/blog/tabular-data-binary-classification-tips-and-tricks-from-5-kaggle-competitions)
More detailed analysis is available at the folloing [link](https://zeevush0819.medium.com/sparkify-523e800cdb59)
