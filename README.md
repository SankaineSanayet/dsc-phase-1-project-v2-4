# Project Title

Microsoft Movie Studio: Data Analysis and Recommendation

## Overview

Microsoft's aim is to venture into the entertainment and media industry. Their main focus is movie production thus there is a need to understand the process of video creation, the budget and the steps required to make it successful. It is also essential for the company to understand the industry well enough to the point where they will avoid mistakes made by other companies, infiltrate the gaps in the industry and introduce new strategies and better services for maximum profit.
In this report, data-driven insights have been provided to aid Microsoft in making the right decisions while venturing into the industry. The aim is to analyze the current trends in the industry, and identify the most successful movie sets based on title, language, genre, and target groups for different movie categories. With such insights, Microsoft company is able to make decisions based on the findings that will propel their business toward success.


## Prerequisites

 software/tools needed to run the analysis:

- Python 
- Jupyter Notebook
- Pandas libraries
- Matplotlib

## Data Sources
The data in use has been sourced from the IMDB box set and Box Office Mojo set. The IMDB box set data is in an SQLite database while the Box Office Mojo set is in CSV format. The data in CSV format is read by loading it into a DataFrame while the SQLite data is read by connection to the database.

## Getting Started

Provide instructions on how to get started with your analysis. Include the following steps:

1. Fork this repository.
2. Clone it into the local computer
3. Open the student.ipynb file
4. Connect the datafile to the SQLite database and read the CSV file by loading it into a DataFrame

## Running the Analysis

1.  Open Jupyter Notebook
    - On git bash terminal navigate to the directory where the `student.ipynb` file is located. 
    - Launch Jupyter Notebook from the git bash terminal
    - Open the Jupyter Notebook by clicking on `student.ipynb`.
2.  Import the necessary libraries
     -Execute the cell to ensure the libraries are loaded into the file.
3.  Connect the im.db file to the SQLite database
     -Write a code that allows us to read the file from the database through creating a connection.
     -Execute the cell to ensure a connection has been created.
4.  Execute queries on the database
     - Once the connection has been created, you are able to read the data and query it
     - Clean the data by dropping the rows with null values(average rating and genre columns contained null valus)
     - Execute the dropna() function ny running the cell
     - Select the tables you are interested in(movie_ranking and movie_basics)
     - Use the different columns (title, average rating, genres, year,numvotes, movie id) to query the database
     - The title and average rating columns are used to get the top most-rated movies.
     - Use the movie id as the common identifier when joining the two different tables.
     - Create a query that outputs the most popular genres based on average rating and mode
     - Visualize the data on a bar graph which shows the performance of different genres over the past years
5. Read the CSV file by loading it into a DataFrame
    - Locate the CSV file (`bom.movie_gross.csv`) a DataFrame.
    - Ensure that the CSV file is available in the same directory.
    - Execute the cell to load the data
6. Perform data cleaning on the data on the file
    -Identify the columns with null values
    -Drop the rows by executing the cell with the dropna() function command
7. Merge the two files in order to draw better conclusions
    - Merge the two datasets using the common column which in this case is the title and year
    - Execute the cell to combine the data from the SQLite database and the CSV file for comprehensive analysis.
8. Analyze the data and perform EDA on it
   - Write a code to show the correlation between domestic gross and foreign gross
   - Write a code to show the trend of the gross incomes, and rating behavior over the years
9. From the drawn conclusions, visualize the outputs
    -To show correlation use a scatter plot
    -To show trends use a frequency graph
10. Close the database by typing conn.close()

## Results

Through my analysis, I identified the top most 3 most-watched movie genres based on ratings. The genres are Documentary, Drama, and Comedy. Documentary movies also happen to hold the largest share in the datasets as uploaded movies on the site.
The scatter plot also proves that both domestic and foreign gross are independent of each other. The densely situated dots on the left lower corner indicated that both incomes were very low at some point. The scattered dots towards the right upper corner indicate that over a certain period of years, the incomes were very high. 
The graph showing the trend of both domestic and foreign gross over the years indicates that foreign gross income is higher.
The limitation I particularly encountered was a lack of recent or up-to-date data on the sets. Most of these data date back to 2019 thus the findings are not quite resourceful and reliable as a lot has changed over the recent years. 

## Recommendations
I would recommend focusing more on individual data and trying to less generalize it. For example, genre-specific data. More data on untouched areas should also be availed for example competitor data, movie reviews and sentiment analysis. This will help in pulling better insights from the analysis.
The data provided should also be up to date in order to deduce meaningful and reliable insights from the analysis.
In the future, a plan to regularly conduct sentiment analysis in order to gauge audience preferences, explore international markets for expansion opportunities, monitor the movie industry trends, and adapt strategies accordingly should be deduced.


## Insights

From the analysis, certain actionable insights have been discovered that would be valuable to Microsoft company for their new movie studio.
First, the company will be able to focus on the movie genre with the highest based on viewer ratings and the number of movies that exist in that category in the box sets. In this case, between the years 2009 and 2019, the documentary genre has had the best performance.
Through the release years, the company will be able to develop a release schedule in order to capitalize on seasonal trends.
Based on the foreign and domestic gross trend graph, Microsoft establishes that most of the income roots from outside their country thus focusing their production and target markets in foreign countries.


## Author

Sanayet Nelly Sankaine
sankainesanayet@gmail.com
0702759871


## Acknowledgments

During my analysis accessed some resources on w3schools and YouTube (Alex the Analyst)









    
   
  













## Summary

This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!
