# Project Title

Microsoft Movie Studio: Data Analysis and Recommendation

## Overview

Microsoft aims to venture into the entertainment and media industry. Their main focus is movie production thus there is a need to understand the process of video creation, the budget and the steps required to make it successful. It is also essential for the company to understand the industry well enough to the point where they will avoid mistakes made by other companies, infiltrate the gaps in the industry and introduce new strategies and better services for maximum profit.
In this report, data-driven insights have been provided to aid Microsoft in making the right decisions while venturing into the industry. The aim is to analyze the current trends in the industry, and identify the most successful movie sets based on title, language, genre and target groups for different movie categories. With such insights, Microsoft company is able to make decisions based on the findings that will propel their business towards success.


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
2. Clone it into local computer
3. Open the student.ipynb file
4. Connect the datafile to the SQLite database and read the CSV file by loading it into a DataFrame

## Running the Analysis

1. Open the Jupyter Notebook file: `student.ipynb`.
3. Import the necessary libraries
4. Connect the im.db file to the SQLite database
5. Read the file and execute queries
6. Read the CSV file by loading it into a DataFrame
7. Perform data cleaning on the data on both files
8. Merge the two files in order to draw better conclusions
9. Analyze the data and perform EDA on it
10. From the drawn conclusions, visualize the outputs
11. Close the database by typing conn.close()

## Results

Through my analysis, I identified the top most 3 most watched movie genres based on ratings. The genres are Documentary, Drama and Comedy. Documentary movies also happen to hold the largest share in the datasets as uploaded movies on the site.
The limitation I particularly encountered was a lack of recent or up-to-date data on the sets. Most of these data date back to 2019 thus the findings are not quite resourceful and reliable as a lot has changed over the recent years. 

I would recommend focusing more on individual data and try to less generalize it. For example, genre-specific data. More data should also be availed for example competitor data, movie reviews and sentiment analysis.
The data provided should also be up to date in order to deduce meaningful and reliable insights from the analysis.
In the future a plan to regularly conduct sentiment analysis in order to gauge audience preferences, explore international markets for expansion opportunities, monitor the movie industry trends and adapt strategies accordingly should be deduced.


## Recommendations

From the analysis, certain actionable insights have been discovered that would be valuable to Microsoft company for their new movie studio.
First, the company will be able to focus on the movie genre with the highest based on viewer ratings and the number of movies that exist in that category in the box sets. In this case, between the years 2009 and 2019, documentaries genre has had the best performance.
Through the release years, the company will be able to develop a release schedule in order to capitalize on seasonal trends.


## Author

Sanayet Nelly Sankaine
sankainesanayet@gmail.com
0702759871


## Acknowledgments

During my analysis accessed some resources on w3schools and YouTube (Alex the Analyst)









    
   
  













## Summary

This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!
