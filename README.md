# Movies Revenue

<img src="https://github.com/silviagonzalez98/Movies-Box-Office-Revenue/blob/main/images/descarga.jpeg?raw=true.png" width="500" />

### About the project

The goal of this project is to build a regression model that is able to predict the revenue of films in box office and explore what features make a film a potential revenue success.

I worked with a dataset that I got from IMDB API. 

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
|Popularity	| Ranking of popularity|
|Runtime|	Lenght of film|
|Vote average	|	Average movie rating|
|Vote count |	Total movie ratings|
|Cast |	Actors involved in the movie|
|Month	|	Movie release month |
|Genres	|	Movie genre|
|Production companies	| Companies involved in the movie|
|Director | Movie directoy|
|	Original language|	Initial language of movie|
|	Language|	Languages of movie|
|Keywords |	Attributes relationed to the movie|

### Data processing


### Conclusions
- Insight 1: Customers who accepted the offer generally have higher quarterly balances. <br /> 
- Insight 2: There is definitely observed a huge jump in average balance from q1 to q2 for households with size 8, and the main reason is that there is only one customer in the dataset that represents household = 8, consequently moves all the metric. <br /> 
- Insight 3: Customers that accepted the offer mostly had received a postcard, and had a low (and medium) credit rating. This results a key piece of information to encourage the bank to focus on prioritizing postcards and focusing on low to meidum credit rating customers. <br /> 
- Insight 4: Categorizing by average balance, most customers (out of 18k) have a balance of 1.4k or less (13.8k customers between 701 to 1.4k balance, and 3.2k customers between 0 to 700 balance).

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
