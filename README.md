# Exploratory Data Analysis With Movies: Phase 1 Project

## Project Overview
Nowadays companies are beginning to realize the importance of data availability in large amounts which allows them to infer meaningful results and make informed business decisions. With development of new technologies, Internet and social networks, production of digital data is constantly growing. To get the most out of data, a robust and thorough data analysis process is needed. This project uses exploratory data analysis to generate insights from the movie industry for use by Microsoft Company.

### Business Problem

Microsoft wants to join the movie industry, however they have no prior knowledge of the industry and they need help so that their movie studio can be successful. This project is aimed at exploring what types of films are currently doing the best at the box office then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

Data was obtained from several sources namely; Box Office Mojo, IMDB, Rotten Tomatoes,TheMovieDB and The Numbers. 
In the folder `zippedData` datasets for movies were provided.

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

The exploratory data analysis process required skills like webscraping, storing and cleaning of data in a pandas dataframe and visualization using seaborn and matplotlib so as to convert the data into an easy to process format.

## Genres and average rating
From the analysis, Documentaries had the highest average rating.
![image](https://github.com/JMangoka1/dsc-phase-1-project/assets/145416424/709cfd15-09b3-486b-a8c0-874d72532140)

## Relationship between movie runtime_minutes and averagerating
It was observed that movies with average runtime minutes have the highest rating
![image](https://github.com/JMangoka1/dsc-phase-1-project/assets/145416424/590d7b4b-2f5f-459e-88e4-ae28b81574b9)

## Preferred months of the year to release a movie
From the analysis highest number of movies are produced in the months of May and December
![image](https://github.com/JMangoka1/dsc-phase-1-project/assets/145416424/a199c1c5-d6d7-4b07-9246-3a9d5c352f81)

## Production budget Vs Profit Margins
Microsoft should budget at least $300M for a movie and that budget should correlate with a profit margin of 85%.

![image](https://github.com/JMangoka1/dsc-phase-1-project/assets/145416424/e2cf9fd4-b654-4535-b72d-04a58dba7ef3)


## Conclusion
Microsoft should take into consideration the rating of their movies based on genre and average runtime minutes as they have highest ratings

## Recommendations
From the data analysis i recommend that Microsoft;

Releases the bulk of their movies in May and December

Consider Documentaries as they have the highest ratings

Microsoft should budget at least $300M for a movie and that budget should correlate with a profit margin of 85%.

Interrogate Deep Throat movies to understand the concepts and success in achieving highest profit margins

Learn from BV studios who will be their top competitor in terms of foreign gross revenues

## Next steps
Exploratory Analysis was used to make recommendations for this project. However, there exists other data analysis methods that can be used to make more accurate recommendations like linear regression models to predict profits based upon one or more variables.Being an introductory project in the data science learning process, it would be exciting to revisit the data after gaining more data science skills to improve on current recommendations
