# nosql-challenge

For this challenge, I set up a Mongo Database and utilized two Jupyter Notebooks for the analysis of the data.


# Part 1: Database and Jupyter Notebook Set Up

I created a MongoDB database and loaded data from the establishments.json file from the Resources folder to the database.


# Part 2: Update the Database

I used one of the Jupyter Notebooks called NoSQL_setup_starter.ipynb.

1. I updated the database on the establishment "Penang Flavours."

2. I removed establishments from the database with the Local Authority from Dover.

3. After the update, I did a few converstions of data types. I converted the latitude and longitude values from strings to decimal numbers. Then, I converted the RatingValue values from strings to integers. Both using the update_many method.


# Part 3: Exploratory Analysis

I used the other Jupyter Notebook called NoSQL_analysis_starter.ipynb. I had to answer the following four questions:

1.  Which establishments have a hygiene score equal to 20?

2.  Which establishments in London have a RatingValue greater than or equal to 4?

3.  What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

4.  How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.


The answers to these questions:

1.  There was a total of 41 establishments that fit the parameter. Refer to the Jupyter notebook for a list of the first 10 establishments that were found for the query.

2.  There was a total of 1004 establishments that fit the parameter. Refer to the Jupyter notebook for a list of the first 10 establishments that were found for the query.

3.  The top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, and nearest to "Penang Flavours" were:
       - TIWA N TIWA African Restaurant Ltd
       - Fineway Cash & Carry
       - Lucky Food & Wine
       - Premier Express
       - Everest Stores Ltd

4.  The folowing were the counts for each Local Authority area based on the parameters posed in the question:
       - Local Authority: Thanet, count: 1130
       - Local Authority: Greenwich, count: 882
       - Local Authority: Maidstone, count: 713
       - Local Authority: Newham, count: 711
       - Local Authority: Swale, count: 686
       - Local Authority: Chelmsford, count: 680
       - Local Authority: Medway, count: 672
       - Local Authority: Bexley, count: 607
       - Local Authority: Southend-On-Sea, count: 586
       - Local Authority: Tendring, count: 542
