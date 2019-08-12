

# Supervised Learning - Project Guidelines


## Introduction

In this lesson, we'll review all the guidelines and specifications for the project.


## Final Project Summary

Congratulations! You've made it through 2 weeks of intense training, and now you're ready to show off your newfound Machine Learning skills!

![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-mod-5-project/master/smart.gif)

We'll be capping the data science portion with a final project, before moving on to a few final days learning the fundamentals of data engineering. Let's dig into the specifications for the project.

## The Project

For this project, you're going to select a dataset and answer a question of your own design using supervised learning. You'll start by identifying a problem you can solve with classification or regression, and then identify a dataset. You'll then use everything you've learned about Data Science and Machine Learning thus far to source a dataset, preprocess and explore it, and then build and interpret a model that answers your chosen question. In the next class, you'll present your results. 


### Selecting a Data Set

We encourage you to be very thoughtful when identifying your problem and selecting your data set--an overscoped project goal or a poor data set can quickly bring an otherwise promising project to a grinding halt.

To help you select an appropriate data set for this project, we've set some guidelines:

1. Your dataset should work for classification or regression. For classification, the task can be either binary or multiclass.

2. Your dataset needs to be of sufficient complexity. Try to avoid picking an overly simple dataset. Try to avoid extremely small datasets, as well as the most common datasets like titanic, iris, MNIST, etc. We want to see all the steps of the Data Science Process in this project--it's okay if the dataset is mostly clean, but we expect to see some preprocessing and exploration. See the following section, **_Data Set Constraints_**, for more information on this.   

3. On the other end of the spectrum, don't pick a problem that's too complex, either. Stick to problems that you have a clear idea of how you can use machine learning to solve it. For now, we recommend you stay away from overly complex problems in the domains of Natural Language Processing or Computer Vision--although those domains make use of Supervised Learning, they come with a lot of other special requirements and techniques that you don't know yet (but you'll learn soon!). If you're chosen problem feels like you've overscoped, then it probably is. If you aren't sure if your problem scope is appropriate, double check with your instructor!  

### Data Set Constraints

When selecting a data set, be sure to take into consideration the following constraints:

1. Your data set can't be one we've already worked with so far during the training.
2. Your data set should contain a minimum of 1000 rows.    
3. Your data set should contain a minimum of 10 predictor columns, before any one-hot encoding is performed.   
4. Once you've selected a dataset and come up with a question to answer, be sure to clear these with your instructor. 

### Problem First, or Data First?

There are two ways that you can about getting started: **_Problem-First_** or **_Data-First_**.

**_Problem-First_**: Start with a problem that you want to solve with classification, and then try to find the data you need to solve it.  If you can't find any data to solve your problem, then you should pick another problem.

**_Data-First_**: Take a look at some of the most popular internet repositories of cool data sets we've listed below. If you find a data set that's particularly interesting for you, then it's totally okay to build your problem around that data set.

There are plenty of amazing places that you can get your data from. We recommend you start looking at data sets in some of these resources first:

* [UCI Machine Learning Datasets Repository](https://archive.ics.uci.edu/ml/datasets.html)
* [Kaggle Datasets](https://www.kaggle.com/datasets)
* [Awesome Datasets Repo on Github](https://github.com/awesomedata/awesome-public-datasets)
* [New York City Open Data Portal](https://opendata.cityofnewyork.us/)
* [Inside AirBNB ](http://insideairbnb.com/)


## The Deliverables

Your completed should contain the following deliverables:

1. A **_Jupyter Notebook_** containing any code you've written for this project.  

3. An **_"Executive Summary" PowerPoint Presentation_** that gives a brief overview of your problem/dataset, and each step of the OSEMN process.



### Jupyter Notebook Must-Haves

For this project, your jupyter notebook should meet the following specifications:

**_Organization/Code Cleanliness_**

* The notebook should be well organized, easy to follow, and code is commented where appropriate.  
    * Level Up: The notebook contains well-formatted, professional looking markdown cells explaining any substantial code. All functions have docstrings that act as professional-quality documentation.  
* The notebook is written to technical audiences with a way to both understand your approach and reproduce your results. The target audience for this deliverable is other data scientists looking to validate your findings.  

**_Process, Methodology, and Findings_**

* Your notebook should contain a clear record of your process and methodology for exploring and preprocessing your data, building and tuning a model, and interpreting your results.
* We recommend you use the [OSEMN process](https://towardsdatascience.com/5-steps-of-a-data-science-project-lifecycle-26c50372b492) to help organize your thoughts and stay on track.

### Executive Summary Must-Haves

Your presentation should contain between 5-10 professional quality slides detailing:

- A high-level overview of your methodology and findings, including the 5 zipcodes you recommend investing in
- A brief explanation of what metrics you defined as "best" in order complete this project

This prresentation should also:

- Take no more than 5 minutes to present
- Avoid technical jargon and explain results in a clear, actionable way for non-technical audiences.

Remember--your results are only as good as your ability to communicate them to stakeholders! 
