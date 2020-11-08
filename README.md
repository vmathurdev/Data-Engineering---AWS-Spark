# Data-Engineering---AWS-Spark

# Introduction

Each year, over 3 million college applications are filed in the US by about 750,000 students, an average of 4 applications per student. Each of them comes with a certain element of randomness or chance. The intended meritocracy inherent in college admissions gives way to uncertainty, doubt, and anxiety, even for students with exceptional credentials. There are many factors that influence admission decisions. Using regression analysis on the given graduate admissions data can give us an idea as to the likelihood of a student getting admitted into a university given the strength of their profile. The predicted output can be helpful to students as it can give them a fair idea about their chances for admission to a particular university. The motivation for choosing this dataset was to primarily fulfil this objective. As a student who has gone through the rigors of the admissions process such an analysis can be very helpful in gauging expectations and also aid students in smartly planning the admission application process. The data was sourced from kaggle.com. Originally, this data was extracted from the applicant’s database of UC Berkley. This dataset consists of multiple quantitative measures of a student’s performance such as GRE and TOEFL scores which are crucial in determining admissions into institutions.

Process and Code Walkthrough

The pipeline for this analysis comprised of the following steps-

Initializing the spark environment
Reading the data from the csv into a spark dataframe
Creating s3 bucket and dumping the data there
Writing parquet to s3 bucket and moving the data
Creating a dataframe from parquet
Exploring the data
Model building – feature selection, vectorization
Fitting a linear regression model
Visualization of model fit
Evaluation of predicted results
