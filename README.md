# tmdb-movies-py
Python Jupyter notebook to analyze movies data
The used dataset is “The Movie Database”.  This data set contains information about 10,000 movies collected from The Movie Database (TMDb) including user ratings and revenue.
Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. There are some odd characters in the ‘cast’ column. 
The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

The dataset for movies list was ready in excel document. I read the data from excel file and put it into data frame. Then I had a general look over the dataset. The dataset has information about 10866 (rows) movies with 21 different information for each movie (columns). I checked the types of columns and if there are any null values. 
Data Cleaning includes:
1.	Convert (release date) into type of DateTime. 
2.	Remove duplicate rows from dataframe
The dataset was assessed and necessary cleaning steps were performed as documented above. Datatypes were made relevant to the context of the columns, duplicates were removed and zeros and null values were dealt with under the exploration of each research question, according to the reasoning provided. Removal of rows containing nulls and/or zeros reduced the data available for analysis, which may impact the results. The correlations explained do not imply causations. The inferences made are tentative and have scope for further refinement. The analysis identifies the top 20 highest grossing movies, top 20 most expensive movies, months with the most movie releases, and top 20 directors based on the rating of their films The analysis also explores the correlation of budgets with revenues, association of month of release with better revenues, and correlation of ratings with commercial success.

