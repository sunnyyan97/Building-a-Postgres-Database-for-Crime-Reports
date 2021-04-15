# Building-a-Postgres-Database-for-Crime-Reports

In this project, I built a Postgres database for storing data related to crimes in Boston. Within this database, I create a schema and tables, as well as users and groups to grant permissions. I also optimize each column of this database to improve run times and storage needed.



In this project I built a database for storing data of crimes committed in Boston with Postgres. The dataset is available in the file boston.csv

Here are a description of some of the columns

-incident_number- represents the identifier of the crime    
-offense_code- numeric identifier code for the committed crime  
-description- a description of the crime  
-date- date crime occurred  
-day_of_the_week- Day of the week crime occurred  
-lat- latitude coordination where crime occurred  
-long- longitude coordination where crime occurred  

The goal of this project was to create a database that is named crimes_db with a table- boston_crimes - that stores the data from the boston.csv file. The boston_crimes table will be contained inside of a schema that is named crimes.

I will also create two groups that can access the database; one readonly group and one readwrite group. The readonly group represents Data Analysts who would use this database to Select files to do their analysis. The readwrite group represents Data Scientists who would Select and Edit Files but not able to delete tables. Finally, I will create one and add a user for each of the groups.
