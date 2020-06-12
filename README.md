# JantaHack_HR_Analytics
Janta Hack HR Analytics hackathon

Problem Statement:
A training institute which conducts training for analytics/ data science wants to expand their business to manpower recruitment (data science only) as well. 
 
Company gets large number of signups for their trainings. Now, company wants to connect these enrollees with their clients who are looking to hire employees working in the same domain. Before that, it is important to know which of these candidates are really looking for a new employment. They have student information related to demographics, education, experience and features related to training as well.
 
To understand the factors that lead a person to look for a job change, the agency wants you to design a model that uses the current credentials/demographics/experience to predict the probability of an enrollee to look for a new job.

Data Dictionary

Variable	Description	Need for cleaning
enrollee_id	Unique ID for enrollee	-
City	City code	Yes. Frequency encoding required.
city_development_index	Developement index of the city (scaled)	-
Gender	Gender	Yes. Missing values. Fill Nas
relevent_experience	Relevent experience	Yes. Label Encoding 
enrolled_university	Type of University course enrolled if any	Yes. Ordinal encoding, missing values.
education_level	Education level	Yes. Ordinal Encoding, missing values
major_discipline	Major discipline	Yes. Mean Encoding
experience	Total experience in years	Yes Recoding the data
company_size	No of employees in current employer's company	Recode(Date Scenario) and Encode with small to large
company_type	Type of current employer	Yes. Encode data
last_new_job	Difference in years between previous job and current job	Yes. Encode
training_hours	training hours completed	Apply logarithms 
target	0 – Not looking for job change, 1 – Looking for a job change	-
 

