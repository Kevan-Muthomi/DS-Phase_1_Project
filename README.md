# Using Exploratory Data Analysis to Generate Insights for Microsoft's New Movie Studio 
   by Kevan Muthomi Ndwiga
## Introduction
Over the years, Microsoft has seen multiple 'big' companies such as Box Office Mojo, IMDB, The Numbers, The Movie, and Rotten Tomatoes venture into the creation of movies and they have observed the need to delve into the industry which seems rather lucrative as attributed to the success of the featured films at the box office. 

To achieve this, they intend to conduct research in the industry and come up with decisions that may inform their movie creation strategy

## Problem Statement
Microsoft's new movie studio aims to enter the competitive film industry by creating original content. However, lacking expertise in movie production, the studio faces the challenge of understanding the dynamic landscape of successful movies at the box office. 

The objective is to leverage exploratory data analysis (EDA) on diverse movie datasets from sources like Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers to identify and interpret trends, patterns, and influential factors contributing to box office success. By extracting actionable insights, the studio seeks to inform strategic decisions regarding the types of films to produce, considering genre preferences, budget allocation, critical ratings, and audience reception.

Ultimately, this analysis aims to guide Microsoft's new movie studio in crafting a targeted content creation strategy aligned with market demands and audience expectations.

## Main Objective 
To conduct an exploratory data analysis (EDA) on diverse movie datasets sourced from Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers. The goal is to derive actionable insights that will aid Microsoft's new movie studio in making informed decisions about the types of films to produce for successful entry and sustainability within the competitive movie industry.

## Specific Objectives
 ### 1. Data Collection and Integration:
Gather and integrate movie data from multiple sources (Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, The Numbers) into a cohesive dataset for analysis.

 ### 2. Data Cleaning and Preparation:
Standardize data formats, handle missing values, remove duplicates, and ensure data consistency for accurate analysis.

 ### 3. Exploratory Data Analysis (EDA):
Identify and analyze trends in box office performance over time.
Explore correlations between movie attributes (genres, ratings, budgets) and box office success.
Examine audience preferences based on ratings from various platforms.

 ### 4. Visualization and Insights Generation:
Create visual representations (charts, graphs, plots) to effectively communicate findings.
Derive actionable insights such as successful genres, optimal budget ranges, the impact of critical ratings, and evolving audience preferences.

 ## 5.Recommendations:
Provide clear recommendations for the types of films the studio should consider producing based on identified successful trends and insights from the analysis.

## 6.Strategic Decision Support:
Equip the head of Microsoft's new movie studio with comprehensive data-backed insights to guide strategic decisions regarding content creation strategies aligned with market demands and audience preferences.

## Notebook Structure
- Reading the data
- Data Wrangling
- Exploratory Data Analysis
- Conclusions
- Recommendations

## Data Understanding
The data used in this project was obtained from various movie content service providers such as Rotten Tomatoes, The Movies DB, Box Office Mojo, IMDB, and The Numbers DB.
The data sets contain the following information:
   - **Rotten Tomatoes** : It has 2 datasets:
        1. `rt.reviews` which includes the fields `id`, `review`, `rating`, `fresh`, `critic`, `top_critic`, `publisher`
           
        2.  `rt.movie_info` which includes the fields `id`, `synopsis`, `rating`, `genre`, `director, writer`, `theater_date`, `dvd_date`, `currency, box_office`, `runtime`, and `studio`.
          
   - **The Movies DB**: It has one dataset `tmdb.movies`, which contains the fields: `genre_ids`, `id`, `original_language`, `original_title`, `popularity`, `release_date`, `title`, `vote_average`, and `vote_count`
     
   - **Box Office Mojo**: It has one dataset `bom.movie_gross` which has the fields `title`, `studio`, `domestic_gross`, `foreign_gross`, and `year`.
   
   - **IMDB**: It is a SQL database that contains 8 tables: `movie_basics`, `directors`, `known_for`, `movie_akas`, `movie_ratings`, `persons`, `principals`, and `writers`.
   
   - **The Numbers DB**: It has one dataset `tn.movie_budgets` which contains the `fields id`, `release_date`, `movie`, `production_budget`, `domestic_gross`, and `worldwide_gross`

## Methodology
### - Data Wrangling
Out of the several datasets that were collected, only some features and rows are relevant to the process. Therefore, in this step, the features that are not required from each dataset were dropped. 

### - Exploratory Data Analysis



## Conclusions
- The 5 most popular genres from the data above are : 
    1. Drama
    1. Comedy
    1. Action and Adventure
    1. Romance
    1. Thrillers

- The movies of the genre Action have the best box office performance. This is attributed to the box office earnings

- The movies with the highest ratings and best reviews are positively correlated with performing well at the box office

## Recommendations
- Microsoft Studio should consider releasing movie content that revolves around the 5 most popular genres above due to their popularity which is a significant fact to consider since popularity is generally attributed to box office success.

- Microsoft Studio should also consider focusing on ratings and reviews from different movies. This will help in coming up with better-informed decisions that are crucial in determining their success at the box office.

- Microsoft Studio should also consider incorporating much newer movie titles into their lineup of movies. This will assist in maintaining relevance in the box office industry.
