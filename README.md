# Capstone Project
**By _Emmanuel Adams, _Muhammad Al Mahdi, _Imam Hasan Araf, Sunmisola Ogundairo

A repository for all documents and deliverables for the Computing Vision project, serviced by team 7 of Deloitte's AI Academy, cohort 4.

# Overview

Computing Vision (a made-up company for the purposes of this project) sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t have much background in creating movies. We are charged with exploring what types of films are currently doing the best at the box office using different samples of available data. We then will translate those findings into actionable insights that the head of Computing Vision's new movie studio can use to help decide what type of films to create.

# Business Understanding 

Computing Vision is trying to penetrate the movie market that makes original video content. The newly established movie studio would need to priortize certain factors to be successful as they diversify into this new market. Some of the questions they might consider answering as they develop the best strategy to penetrate the market include: 

_What kind of movies do people want to watch?
_How much should we spend on our movies?
_How long should the movies last?
_Where should we launch our content?


# Data Understanding

The data used for this analysis came from Box Office, IMDB, Rotten Tomatoes, Movie DB, and Numbers. Each datatset contains thousands of information describing different kind of details about movies that have been released in the past few years. Some of the descriptors include, ratings, genres, budget, movie title, directors, movie revenue amongst others. 

Consult the Dataset folder in this repo to view the data. 

Note: Large datatsets will be in the .gitignore file

# Data Analysis

To answer the business questions, we begin with data exploration to analyze the data we have. The quality of any dataset is the quality of the analysis and conclusion that can be drawn from such data, at such we started our exploration phase with data cleaning. Upon cleaning the data, we progressed to inserting additional tables to some numeric data. For example, deducing the profits made from production budget and production gross. This allowed us to see hidden features in our data. For data maximization, we also join two tables in a database to  get a more robust data.

Upon cleaning, joining, and appending new columns, we started extracting meaningful information using hypothesis testing, data visualization tools-line graphs, scartter plots and histograms-and other statistical inference tools.

The holistic data analysis approach led to the following recommendations:

1. We used a barplot to illustrate our recommendation on movie budget: Make movies that cost 5 million or lower
2. We used two boxplots to contrast the importance of launching domestically before expanding to foreign markets, this was supported with hypothesis testing
3. Usng a histogram, we identified the top generes with high ratings are Documentary, Drama and Comedy
4. Staistical inference, hypothesis testing and a lineplot helped us illustrate that short movies (56 minutes runtime) have a higher rating  

# Conclusion

Upon completion of this project, we recommend Computing Vision consider 

A. Investing in movies that cost lower than 5 million
B. Launch their movie domestically before expanding to foreign markets
C. Focus on documentary, drama, and comedy genres 
D. Invest in short movies as they plan to begin creating original video content

# Repository File Structure

The repository houses the following:

-Final_Notebook
-Datasets
-IMDB
-Exploratory_Notebook
-.gitignore
-Presentation in PDF
-Final_Notebook in PDF
-README.md 

