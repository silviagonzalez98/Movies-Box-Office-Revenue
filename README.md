# Movies-Box-Office-Revenue

<img src="https://github.com/silviagonzalez98/Movies-Box-Office-Revenue/blob/main/images/descarga.jpeg?raw=true.png" width="500" />

### About the project

The goal of this project is to build a regression model that is able to predict the revenue of films in box office and explore what features make a film a potential revenue success.

I worked with a dataset that I got from IMDB API. After building the model, I analyzed another dataset for checking streaming content trends on Netflix and Amazon Prime (link : https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney).

### Dataset
The data set consists of information on 17,000 current bank customers in the study. The information of the datased includes both categorical and numerical variables to analyse indicated below.

|Categoricals | Values |	
------------- | -------------| 
|Offer accepted	| Yes, No|
|Reward	| Air Miles, Cash Back, Points|
|Mailer type	|	Letter, Postcard|
|Income level	|	High, Medium, Low|
|Overdraft protection |	Yes, No|
|Credit rating	|	High, Medium, Low
|Own your home	|	Yes, No|
|Customer number	| 1 to 18.000|
|	Bank accounts open| 1 to 3|
|	Credit cards held|	1 to 4|
|	Homes owned|	1 to 3|
| Household size|	1 to 9|
|	Average balance|	48 to 3366|
|	Q1 balance|	0 to 3450|
|	Q2 balance|	0 to 3421|
|	Q3 balance|	0 to 3823|
|	Q4 balance|	0 to 4215|

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
