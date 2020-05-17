# Sparkify
<img src="image.jpeg" alt="Udacity" title="Sparkify-churn" style ="width: 1000px;"/>
Analyzed customer activities of a music hosting service using Spark Dataframe and Spark SQL on a 247.6 MB dataset running on IBM Watson Studio.
Built ML Pipeline with Spark ML to predict churn, and achieved 0.74 F1 score and 0.8 accuracy

[Go to blog post!](https://medium.com/@anhchu1291/churn-prediction-for-music-hosting-service-sparkify-5a8d476e5b9b)

## Motivation
This project is part of the requirement for Data Scientist Nanodegree on Udacity to follow a Data Analysis end-to-end process including ETL, Machine Learning and Deployment.

## Project Files
  - **Sparkify.ipynb**: notebook run on the medium dataset run on medium dataset of 247.6 MB ('medium-sparkify-event-data.json')
  - **Sparkify_smallDataset.ipynb**: test notebook run on a small dataset of 128MB ('mini_sparkify_event_data.json')

## Installation/Requirement
The code is written in Python3. To run the Python code, you will need to install necessary packages using pip install or conda install.
You also need to run the Spark Cluster on either Amazon Web Services (AWS) or IBM Cloud. 
If you choose to use AWS, you can use the full 12GB dataset hosted on our public S3 bucket, and expect to use about $30 dollars to run this cluster while you build your project for a week. If you choose to use IBM Cloud, you'll use a medium-sized 23 MB dataset we provide for you to download here. You will still deploy your application on a Spark cluster, but this will not cost you any money.

**The deployment of this project used the medium_dataset 23MB and run on IBM Cloud**

### Create an IBM Cloud Account and Watson Project
Create an IBM Cloud account to use the IBM Watson Studio service.

1. Visit cloud.ibm.com and click on the "Create an IBM account" button.
2. If you have an IBM Cloud account already, sign in.
3. If you do not have an account, sign up.
4. Once you finish signing up, wait a few minutes to receive your IBM Cloud account confirmation email. Then return to cloud.ibm.com and sign in.
5. Register for IBM Watson Studio
  1. Click on the menu icon on the top left and select "Watson." Or just click here. Scroll down and select "Try Watson Studio."
  2. Next, select "Create Project."
6. Hover over "Data Science" and click "Create Project"
  Enter a name for your project and click "Create" on the bottom right.
  
### Launch IBM Cluster and Notebook
1. Click "Add to project" on the top and select "Notebook"
2. Enter a name for your notebook and select "Default Spark Python 3.6" under runtime and click "Create Notebook" on the bottom right.

## Reference
1. Credit to Udacity and the instructional staff for the project guidance and preparation 
2. Other online resources for this project completion:
- https://spark.apache.org/docs/latest/ml-classification-regression.html
- https://docs.databricks.com/applications/machine-learning/mllib/binary-classification-mllib-pipelines.html
- https://medium.com/@dhiraj.p.rai/logistic-regression-in-spark-ml-8a95b5f5434c
- https://databricks.com/session/apache-spark-mllib-2-0-preview-data-science-and-production
