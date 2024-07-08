

# Netflix Mid-2021 Data Analysis

## Table of Contents
- Problem Statement
- Data Source
- Tools
- Data Transformation
- Visualization

### Problem Statement

Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc. I will demonstrate following criterias.

    1. What are total counts based on type?
    2. What are the total counts based on type and country?
    3. Demonstrate the top 5 countries which have filmed movies most.
    4. What are the TV Shows count in the range of 1-5 season, 5-10 season, >10 season
    5. What is the unique genre count?
    6. What is the total movies&tv shows count based on genre?
    7. What are the unique rating types and total movies&tv shows count based on it?
    8. Demonstrate total movie_count and tv shows based on year on the date_added.

### Data Source
The datasets used for this analysis are the "netflix_data.csv" file.

#### Explanation of the data table?
- show_id = Unique Id for every Movie & TV Shows
- type = Identifier ( Movie or TV Show)
- title = Title of the Movie/TV Shows
- director = Director of the Movie/TV Shows
- cast = Casts of the Movie/TV Shows
- country = Country where the movie was produced
- date_added = Date it was added on Netflix
- release_year = Actual release year of the Movie/TV Shows
- rating = TV rating of the Movie/TV Shows
- duration = total duration
- listed_in = Genre
- description = The summary description of the Movie/TV Shows


### Tools
 PowerBI (Data Visualization)

 #### Skills Used

- DAX
- Page Navigation
- Filters
- Modeling
- Power Query
- Formatting visuals
- Concatenate measure with text (for titles)

### Data Transformation
Data cleaning and transformation were made in Power Query.

### Visualization

![HOME PAGE](https://github.com/burcinalim/POWER-BI-PROJECTS/blob/main/03-Netflix%20Mid-2021%20Data%20Analysis/Screenshots/1.png?raw=true)

![MOVIE FIGURES](https://github.com/burcinalim/POWER-BI-PROJECTS/blob/main/03-Netflix%20Mid-2021%20Data%20Analysis/Screenshots/2.png?raw=true)

![TV SHOW FIGURES](https://github.com/burcinalim/POWER-BI-PROJECTS/blob/main/03-Netflix%20Mid-2021%20Data%20Analysis/Screenshots/3.png?raw=true)
