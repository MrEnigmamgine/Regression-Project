# Zillow data property value project
A school project to build a machine learning model to predict property value via regression and deliver a report on the indicators used in the model.

## About the project

The project will attempt to develop a clear understanding of how property values are assessed and deliver a regression modeling solution for predicting a property's value.

### Steps to reproduce
First download a copy of each file or clone this repository.

To run this project you will need to fulfill one of the following requirements:
 > An environment file named `env.py` in the same directory as the other files.  The enviornment file should be structured the same as below and should contain your unique credentials to CodeUp's SQL server.
 ```py
hostname='data.codeup.com'
username='your_username'
password='your_password'
```
> A csv file named `telco.csv` in the same directory as the other files.  You can download a copy of the data from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn?resource=download)

You will also need to ensure the proper libraries are installed in your python environment.  You can install the libraries easily by running the following command in your python shell:
```py
%pip install numpy
%pip install pandas
%pip install matplotlib
%pip install seaborn
%pip install plotly
%pip install scipy
%pip install sklearn
```
___________
### Deliverables

Since the company wants two different things that means that we will need at least two deliverables in our final product:  
 1. A storytelling document that explains at least one driver of property value and makes recommendations on how to discover further.
 2. A machine learning model that predicts the probability of a customer churning that will perform well in production.

Because this is a classroom project there are some additional requirements that will need to be met.  

For the storytelling document:
 - It will need to be delivered in a jupyter notebook named `Final_report.ipynb`
 - It must include 4 visulalizations
 - It must include 2 statistical tests

For the machine learning model:
 - It should be demonstrated in the `Final_report.ipynb` notebook.




Your readme should include a clear project goal that reflect on what you are trying to achieve for the business/organization (in the scenario layed out). Your goal is never just to create an algorithm or model or to purely make discoveries in exploration...it includes the why. 'My goal is to..., so that...' Your goal should be specific enough to know when you have reached it and concise enough to keep in 1-2 sentences. 'My goal is to identify key drivers of churn, which customers at risk of churn, and make recommendations for changes so that we can reduce the monthly churn rate and increase customer retention.' This helps tell you when you have reached a minimally viable product (including a presentation and predictions, in this example scenario).


Your readme should include initial questions and focus you are going into the analysis with. This is an important part of project planning and gives context to the reader about where you started, what were your initial ideas and thoughts, and did those play out to be true.

Your readme should include a project description that provides context for your project, including explaining why you are tackling this project, why it is important and how it could be of use to someone else beyond just the interest or new knowledge. It dives in a bit deeper than the goals. Project description and goals should always be in your words and specific to your project, not a copy of the class project spec.


Your readme should include useful and adequate instructions for reproducing your analysis and final report.

Your readme should include a data dictionary, which is important to provide in order to define and disambiguate each of the variables you are analyzing.

Your readme should include a project plan which helps guide both the user and yourself through the different stages of the pipeline and steps you took to get to your conclusion.