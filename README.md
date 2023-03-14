# Python-and-Spark-for-Big-Data

## About this Repo:
This repository contains course notebooks for *Python and Spark for Big Data*. The course covers an extensive range of topics, including Spark, RDDs, Spark 2.0, Unix command line basics, Jupyter Notebook, Spark DataFrames, machine learning, linear regression, logistic regression, tree methods, clustering, recommender systems, natural language processing, and Spark Streaming.

The course is structured with an introduction, course set-up guide, Spark DataFrames section, machine learning, linear regression, logistic regression, tree methods, clustering, recommender systems, natural language processing, and Spark Streaming. Each section contains comprehensive course materials, including project exercises, solutions, and code-alongs.

The repository is intended to be used as a resource for students who want to learn about Python and Spark for Big Data, but it can also be used by instructors as a supplement to their course materials. The course notebooks are organized in a logical order, making it easy for learners to follow the material and work through the exercises at their own pace.

## Preparing the environment
**Note**: I have tested the codes on __Linux__. It can surely be run on Windows and Mac with some little changes.

1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/iamirmasoud/pyspark_tutorials.git
cd pyspark_tutorials
```

2. Create (and activate) a new environment, named `spark_env` with Python 3.7. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	```shell
	conda create -n spark_env python=3.7.10
	source activate spark_env
	```
	
	At this point your command line should look something like: `(spark_env) <User>:pyspark_tutorials <user>$`. The `(spark_env)` indicates that your environment has been activated, and you can proceed with further package installations.

3. Before you can experiment with the code, you'll have to make sure that you have all the libraries and dependencies required to support this project. You will mainly need Python3.7+ and PySpark. You can install  dependencies using:
```
pip install -r requirements.txt
```

4. Navigate back to the repo. (Also, your source environment should still be activated at this point.)
```shell
cd pyspark_tutorials
```

5. Open the directory of notebooks, using the below command. You'll see all files appear in your local environment; open the first notebook and follow the instructions.
```shell
jupyter notebook
```

6. Once you open any of the project notebooks, make sure you are in the correct `spark_env` environment by clicking `Kernel > Change Kernel > spark_env`.

## Course Outline:

* Course Introduction
    * Promo/Intro Video
    * Course Curriculum Overview
    * Introduction to Spark, RDDs, and Spark 2.0
    
* Course Set-up
    * Set-up Overview
    * EC2 Installation Guide
    * Local Installation Guide with VirtualBox
    * Databricks Notebooks
    * Unix Command Line Basics and Jupyter Notebook Overview
    
* Spark DataFrames
    * Spark DataFrames Section Introduction
    * Spark DataFrame Basics
    * Spark DataFrame Operations
    * Groupby and Aggregate Functions
    * Missing Data
    * Dates and Timestamps
    
* Spark DataFrame Project
    * DataFrame Project Exercise
    * DataFrame Project Exercise Solutions
    
* Machine Learning
    * Introduction to Machine Learning and ISLR
    * Machine Learning with Spark and Python and MLlib
    * Consulting Project Approach Overview
    
* Linear Regression
    * Introduction to Linear Regression 
    * Discussion on Data Transformations
    * Linear Regression with PySpark Example (Car Data)
    * Linear Regression Consulting Project (Housing Data)
    * Linear Regression Consulting Project Solution

* Logistic Regression
    * Introduction to Logisitic Regression 
    * Logistic Regression Example
    * Logistic Regression Consulting Project (Customer Churn)
    * Logistic Regression Consluting Project Solution
    
* Tree Methods
    * Introduction to Tree Methods
    * Decision Tree and Random Forest Example
    * Random Forest Classification Consulting Project - Dog Food Data
    * RF Classification Consulting Project Solutions
    * RF Regression Project - (Facebook Data)
    
* Clustering
    * Introduction to K-means Clustering
    * Clustering Example - Iris Dataset
    * Clustering Consulting Project - Customer Segmentation (Fake Data)
    * Clustering Consulting Project Solutions
    
* Recommender System
    * Introduction to Recommender Systems and Collaborative Filtering
    * Code Along Project - MovieLens Dataset
    * Possible Consulting Project ? Company Service Reviews
    
* Natural Language Processing
    * Introduction to Project/NLP/Naive Bayes Model
    * What are pipelines?
    * Code Along 
    
* Spark Streaming
    * Introduction to Spark Streaming 
    * Spark Streaming Code-along!
 
    
    
    

 