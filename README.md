# dating-data

this dataset is taken from datahub.io and the link to the same is https://datahub.io/machine-learning/speed-dating#python

This dataset is about speed dating.

This data was gathered from participants in experimental speed dating events from 2002-2004. During the events, the attendees would have a four-minute “first date” with every other participant of the opposite sex. At the end of their four minutes, participants were asked if they would like to see their date again. They were also asked to rate their date on six attributes: 

Attractiveness,
Sincerity,
Intelligence,
Fun,
Ambition,
Shared Interests.

The dataset also includes questionnaire data gathered from participants at different points in the process. These fields include: 
demographics,
dating habits,
self-perception across key attributes,
beliefs on what others find valuable in a mate,
and lifestyle information.

there are 123 columns in the dataset with match column as the target variable .the columns were of different datatypes which i changed to be used as a feature in the machine learning model.
the categorical variables were changed through label encoding and the columns with data as an interval were replaced by the average of the interval.i created functions for various works and changed the values in the dataset to numerics to be used in the ml model.

there were null values in the dataset which i filled with mean values of the same column.in some of the columns the null values are replaced with the most occuring element of the column.
the python libraries i used are pandas ,numpy,seaborn,matplotlib,scikit-learn for all the analysing and cleaning work.
as i started data wrangling i saved the dataset twice to keep up with the updated dataset and i have attached both the files here.
train test split from sklearn is used to split the data ,i am splitting the data in the ratio of 90 and 10 with 90% as the train data and 10% as the test data, 10% data for testing the model will be sufficient as we have a good amount of data.
i am using support vector machine for predicting the target variable which is giving a accuracy of 84.4%.

