## Goal
The Goal of this assignment was to create a function that takes in 3 arguments: wikipedia, kagle, and ratings data. Then we were asked to create a dataframe into SQL. 

## Assumptions

We assumed that the files would be in the same format.(JSON & 2 CSV files). Regular expressions were also used on current data, which can be changed at any time. We assumed that an imbd_link only has 7 digits. If ther are any less or more, we would miss them. 

We dropped columns where 90% of the value is null. We want to make sure we are using good and actual data in our set! 

At times, we switched off deciding whether kaggle data or wiki data was more accurate. This could also changed based on new movies/data provided. 

## Process
I imported all our dependencies and information needed for SQL.I created a big function using the three arguments. I read the different files, put them into dataframes, and then starting cleaning each one. This incolved a process of cleaning up names, merging colums, checking accurate alternative information, etc. 

I merged the data frames and attempted to load tables into sql. 
Code- error, but still sent to get partial credit!
