# edX IBM Data Science Capstone Project
This is the capstone project for successfully completing the Professional Certificate program in Data Science by IBM offered on edx.org.

The certificate can be found through the link below:
https://credentials.edx.org/credentials/5bf2a4f1a14f4aaa9dfea8fb3ab16c7d/

# Problem statement
The people of New Yorker use the 311 system to report complaints about the non-emergency problems to local authorities. Various agencies in New York are assigned these problems. The Department of Housing Preservation and Development of New York City is the agency that processes 311 complaints that are related to housing and buildings.

In the last few years, the number of 311 complaints coming to the Department of Housing Preservation and Development has increased significantly. Although these complaints are not necessarily urgent, the large volume of complaints and the sudden increase is impacting the overall efficiency of operations of the agency.

Therefore, the Department of Housing Preservation and Development has approached your organization to help them manage the large volume of 311 complaints they are receiving every year.

The agency needs answers to several questions. The answers to those questions must be supported by data and analytics. These are their  questions:

- Q1: Which type of complaint should the Department of Housing Preservation and Development of New York City focus on first?
- Q2: Should the Department of Housing Preservation and Development of New York City focus on any particular set of boroughs, ZIP codes, or street (where the complaints are severe) for the specific type of complaints you identified in response to Question 1?
- Q3: Does the complaint type that you identified in response to question 1 have an obvious relationship with any particular characteristic or characteristics of the houses or buildings?
- Q4: Can a predictive model be built for a future prediction of the possibility of complaints of the type that you have identified in response to question 1?

Your organization has assigned you as the lead data scientist to provide the answers to these questions. You need to work on getting answers to them in this Capstone Project by following the standard approach of data science and machine learning.

# Structure of the project
The project has been split into four different Jupyter notebooks - each of them corresponding to the four questions above.

## Datasets
### New York City 311 complaints - Raw data
This dataset is available at https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9. You can download part of this data by using SODA API.

It's important to note, that the datasets consists of multiple gigabytes worth of data. Therefore, the raw data can't be uploaded to GitHub. This dataset is used as an import in the very first notebook. The other ones can be executed with the pickle file, that's generated in the end of the first notebook. You can download the file through the following link: https://drive.google.com/file/d/1DZuVO0EOC41m3r-yAGxuQMefUWpglYor/view?usp=sharing

### PLUTO dataset for housing
This dataset for housing can be accessed from https://data.cityofnewyork.us/City-Government/Primary-Land-Use-Tax-Lot-Output-PLUTO-/xuk2-nczf. 

In this project, only the dataset of one particular borough has been used.

## Packages used in the project
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Pingouin 
- Operator
- Math
- Statsmodels
- Scikit-learn
- Imbalanced-learn

## Summary
In the exploratory data analysis, it has been proven that complaints about heating in particular have by far the highest incidence both in the total comparison and in the annual evaluation. The leading region is the Bronx district, which is investigated in more detail in the following. On the basis of variables primarily related to the size of the buildings and the number of residents, a logistic regression model has been defined that demonstrates at a minimum a significant predictive effect for future urban development or planning in order to prevent heating complaints.
