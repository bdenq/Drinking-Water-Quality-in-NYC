#Project Proposal

- This project goes through the process of extracting, transforming, and loading data about drinking water quality in New York City for year 2019 and 2021, using Pandas and PostgreSQL

#Finding Data

- We picked our data for year 2019 from NYC open data and data for 2021 from Kaggle.

#Data Cleanup

- We did some cleaning on our data: replacing some blank cells with "0" value, and filter the data by select years.
- We chose to use pgAdmin as our database and load our data into it.
- Reasons we chose pgAdmin are:
  - It is the most popular platform for PostgreSQL;
  - Features rich open-source development and community;
  - It is highly expandable.
- The final table consists of 8 columns like in the original dataset.
