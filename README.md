# Datascience
---Datascience Related projects

Scrapped and Developed Basic Recommedation System for top 250 IMD movies
Step1:scrapping

1)Scrapped the top 250 movies of IMDB data

2)Columns which were scrapped were:
 Name of the movie 
 - Year released 
 - IMDB rating 
 - Number of reviewers 
 - Censor board rating 
 - Length of the movie 
 - Genre 1 
 - Genre 2 
 - Genre 3 
 - Genre 4 
 - Release date 
 - story summary 
 - Director Name 
 - Writer 1 
 - Writer 2 
 - Writer 3 
 - Star 1 
 - Star 2 
 - Star 3 
 - Star 4 
 - Star 5 
 - Plot Keywords list 
 - Budget 
 - Gross USA 
 - Cumulative worlwide Gross 
 - Production company 
 Step2:Building a Reommadation System
 
 1)After scrapping and stored the data  into the dataframe performed Exploratory Data Analyis(Checking the correlation between columns,inputing NA values)
 
 2)From Keywords column(main plot words) generated a bag of words by the help of count vectorizer . 
 
 3)With the Nearest Neibhours in Sklearn Package would able develop a basic basic reommendation System
 i.e When we give a  movie input it recommends top 10 movies based director,plot,popularity index,genres and stars
