# EVALUATION OF DRUG USAGE
# Business Understanding
### Business Overview
Drug/substance abuse has been and is an increasing problem in the world. A number of studies carried out in various countries show that almost every person at one time or another experiments with drugs and substances especially bhang, alcohol or cigarettes. 
The marked and felt velocity is continually highlighted in the dailies since the major cause of concern is that a significant proportion of people eventually get addicted posing a threat to their own health and safety, while creating difficulties for their families and the public at large.
While globalization has opened opportunities for individuals and communities to increase wealth and spending, it has also widened access to previously restricted products across national boundaries including illicit drugs. 


 
### Business Objective
This project seeks to explore drug/substance abuse in an array of assorted groups of people across different age groups, personalities, education levels and ethnicity. The study was conducted in a number of countries including; Canada, USA, UK, Australia,New Zealand and the Republic of Ireland.



### Business Success Criteria
Identify the most used drug/substance.
Assessing the Situation
Resource Inventory
Datasets:
https://archive.ics.uci.edu/ml/machine-learning-databases/00373/drug_consumption.data 
Software( Github, Google Collaboratory, Python)
Assumptions
The data provided is correct and up to date
Constraints
There are no constraints

### Data Mining Goals
Our data mining goals for this project include:
Analysing the trends of drug abuse among the various age groups, countries, gender, education levels and ethnicity. (Main Objective)
Determining the age group with the highest rate of drug/substance abuse.
Finding out the age group with the lowest rate of drug/substance abuse. 
Establishing the most used drug.
Determining the most used drug among the gender groups, countries, education levels and ethnicity.
 
 

### Data Mining Success Criteria
Our success criteria will be measured by the following criteria;
Identifying the most used drug/substance and the age group and gender that uses it.
	
	
#Data Understanding
Data Understanding Overview
We are going to use the following dataset, gotten from the UCI ML Repository, during this project

https://archive.ics.uci.edu/ml/machine-learning-databases/00373/drug_conSsumption.data 

###Data Description
The available dataset to be used for this project is as follows:
https://archive.ics.uci.edu/ml/machine-learning-databases/00373/drug_consumption.data- This dataset contains data collected on drugs and substances abused by various people from different age groups, gender, countries, ethnicity and education levels. It has 32 attributes and 1885 rows.

###Verifying Data Quality
We reviewed the main data set and performed several data cleaning procedures that included, deleting columns, removing white spaces in column names, checking for missing values and dropping duplicates.

#Data Preparation 
These are the steps followed in preparing the data 
###Importing Pandas and Numpy
We first imported panda and numpy libraries.
###Loading Data 
Then loaded and read  the dataset from a url link and created a pandas dataframe from it.
###Cleaning Data
While exploring our data we realized some columns were redundant and would not serve any purpose in our analysis, hence we deleted them. 
We also changed the column names to upper case and replaced the spaces between column names with an underscore.
We changed the values in the gender column to either male or female.
We also classified the age column values into various age groups.
We changed the values in the country column to the country name they represented.
We then did the same for the ethnicity column which had values that represented the different ethnicities of the respondents that participated in the study.
We checked for and removed white spaces in the column names.
We checked for missing values and deleted them.
The same was done for the duplicates.
The drugs in this data set are categorised into the following classes:
CL0 Never Used
CL1 Used over a Decade Ago 
CL2 Used in Last Decade 
CL3 Used in Last Year 
CL4 Used in Last Month
CL5 Used in Last Week 
We thought it best to narrow them down to two classes namely, users and non-users for better analysis. CL0 and CL1 were combined to form non-user while the rest formed users.
 
#Analysis
During our analysis, we were able to find:
Chocolate was the most used drug with 1850 users, followed closely by caffeine, 1848 users,  and alcohol 1817 users.
Alcohol: Females are the biggest users overall with a total of 910 users.
Amphetamine:  Males are the biggest users overall having a total of 445 users.
Amyl: Males are the biggest users with a total of 236 users. 
Benzos: Males are the biggest users with 446 users.
Caffeine: Males are the biggest users overall with 928 users.
Cannabis: Males are the biggest users with 738 users.
Chocolate: Both males and females have the same number of  users, 925
Cocaine: Males are the biggest users overall having 417 users.
 Crack: Males are the biggest users overall having 135 users.
Ecstasy: Males are the biggest users overall having 483 users.
Heroin: Males are the biggest users overall having 146 users.
Ketamine: Males are the biggest users overall having 244 users.
Legal highs: Males are the biggest users overall having 525 users. 
LSD: Males are the biggest users overall having 392 users.
Methadone: Males are the biggest users overall having 282 users.
Mushrooms: Males are the biggest users overall having 463 users.
Nicotine: Males are the biggest users overall having 703 users. 
Semer: Females are the biggest users overall having 4 users.
Volatile: Males are the biggest users overall having 703 users.

Usage of drugs in the various categories:
Age group: 65+ has the most drug users with caffeine being the most used drug. The age group with the lowest rate of drug abuse is 55-64 years.
Gender - Males are the biggest users, with caffeine being the most used drug.
Countries - USA has the largest number of users with chocolate  being the most used drug. 
Education Level - Doctorate have the most users with chocolate being the most used drug.
Ethnicity - Whites have the most users with chocolate being the most used drug.


 
The full analysis can be found in the  following notebook: [Link]




#Recommendations

-Being the most used drugs : chocolate, caffeine and alcohol, we’d recommend for people to be cautious while consuming  products that contain these components to prevent addiction.
-The government should formulate strategies to sensitize people on chocolate and caffeine consumption because most users might be abusing them unconsciously.

-It is our observation that specific categories i.e males, doctorate students, people aged 65+ years, that are predisposed to high pressure levels abuse drugs/substance the most thus the states should convene  public–private partnerships to implement drug abuse sensitization campaigns with more focus directed on these categories to discourage drug use.

-Extensive research should be carried out to evaluate the factors that lead to most people aged 65 years and above to consume drugs and solutions found to mitigate the problem.

- Drug testing can be a constructive means of helping drug abusers overcome denial of their substance abuse. As a part of intervention, drug testing can be used to help the users achieve and maintain recovery









Evaluation
The evaluation will come after presenting data findings to the concerned parties within the company for them to give their input and decide how to best utilize the new information derived from data analysis.
