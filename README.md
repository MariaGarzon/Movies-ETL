# Extract, Transfrom, Load Movie Data

## Overview

As part of Amazing prime's hackathon that aims to develop an algorithm to predict which low budget movies released will become popular, I gathered data from both Wikipedia and Kaggle, combined and transformed them using python's pandas library, and saved them into a SQL database so that the hackathon participants have a nice, clean dataset to use. 

## Results 

After extracting the Wikipedia and Kaggle data from their respective files, transforming the datasets by cleaning them up and joining them together, and loading the cleaned dataset into a SQL database, I creaded two tables:
           
            a) The movies table consists of 31 features for 6052 movies. 
![Movies Query](https://github.com/MariaGarzon/Movies-ETL/blob/9074a89ff79f87d8b6195298392fe1490b7b45b3/images/movies_query.png)
            
            b) The ratings table consists of 5 features for 26 million individual user ratings.
![Ratings Query](https://github.com/MariaGarzon/Movies-ETL/blob/9074a89ff79f87d8b6195298392fe1490b7b45b3/images/ratings_query.png)

These tables will assist students in the process of develping a successful algorithm and derive favourable insights. 
            
