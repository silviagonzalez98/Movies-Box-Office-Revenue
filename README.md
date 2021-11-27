# Movies Revenue

<img src="https://github.com/silviagonzalez98/Movies-Box-Office-Revenue/blob/main/images/descarga.jpeg?raw=true.png" width="500" />

### About the project

The goal of this project is to build a regression model that is able to predict the revenue of films in box office and explore what features make a film a potential revenue success.

I worked with a dataset that I got from TMDB API. 

After building the model, I analyzed another dataset for checking streaming content trends on Netflix and Amazon Prime (link : https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney).

### Dataset
The data set consists of information on 8.000 films from 1990 until 2020. 

The information of the datased includes both categorical and numerical variables to analyse indicated below:

|Column | Description |	
------------- | -------------| 
|ID|	Movie ID|
|Title|	Name of the movie|
|Budget	| Sum of film production cost|
|Overview|	Description of the movie|
|Cast |	Actors involved in the movie|
|Month	|	Movie release month |
|Genres	|	Movie genre|
|Production companies	| Companies involved in the movie|
|Director | Movie director|
|	Original language|	Initial language of movie|
|	Language|	Languages of movie|
|Keywords |	Attributes relationed to the movie|
|Popularity	| Ranking of popularity|
|Runtime|	Lenght of film|
|Vote average	|	Average movie rating|
|Vote count |	Total movie ratings|
|Revenue |	Total revenue of film|

### Project workflow

1. Data extraction
- File: a) data extraction - tmdb api.py
- Extracted 8.000 films from TMDB API with 23 different features to analyze and predict box office revenue
- Additionally, extracted an opensource dataset from Kaggle with streaming films to film market trends with tableau

2. Data cleaning
- File: b) data cleaning.ipynb
- Manipulated dataframe from json format columns and deleted empty columns with Python
- Prepared the dataset for the data visualization part.

3. Data visualization
- File: c) data visualization.ipynb
- Visualized both numericals and categoricals variables to see influences on revenue
- Categoricals: Explored most relevant features for revenue in each column to hot encode them
- Concluded visually  most important categoricals to encode in EDA

4. EDA & Regression Model
- File: d) EDA & regression.ipynb
- Exploratory data analysis
- Data processing of numericals and one hot encoding of relevant categoricals based on data visualization
- Feature engineering & Model evaluation
- Results: LR: 0.8 / KNN = 0.72 / Random Forest: 0.81

5. Presentation
- File: Presentation l Final Project.pdf
- Used Python work and Tableau for presenting the key findings on revenue features
- Used Tableau to analyze trends from Kaggle dataset
- Concluded with most important features to consider for selecting the next year portfolio of movies


### Conclusions to Select Next 2022 Film Portfolio
1. Revenue strong correlation with film budgets and vote count, while less relationship with film vote average
2. Summer (June-July) and Christmas (November-December) best months to release a movie
3. Warner Bros, Paramount, Universal Pictures, 20th Century Fox, Columbia Pictures: drive x2 average revenue film
than the rest
4. Animation and Adventure genres demonstrated to be the most profitable and loved in the market. Music as
possible potential genre if it had more budget
5. Documentary as possible opportunity to further revenue growth. Drama streaming trend focus over last years.
6. India boosting in the streaming content landscape and becoming most valued film country to focus on

### Libraries

Libraries
------------- |
|	pandas as pd |	
|	numpy as np |	
|	warnings |	
|	matplotlib as plt |	
|	seaborn as sns |	
|	scipy |	
|	imblearn |	
|	sklearn |	
