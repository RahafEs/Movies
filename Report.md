

## Abstract:


- Prediction of the correct IMDB gross is essential for the movie industry and decreasing market risk. 
  The success and failure of the movie depend on movie-related variables.
  Therefore, the goal of this project is to create a machine learning model that will predict the US movies gross taking into consideration many features.
  The features include IMDb rating, certification of movie, number of votes, release year, movie duration, and metascore. 
  Exploring data scraped from the IMDb websites to see which features affect the prediction the most.


## Design:


- The progress of this project will be as follows.
  First gathering data using web scraping but the data was so small 1k abservation and then we decided to choose another dataset from Kaggle 5k abservation , 
  then exploratory Data Analysis (EDA) will be performed on the data we gathered. Finally, preparing data to be used in different regression models.
  In this project, we analyze the relationship between the target variable “Gross” and the features “duration, num_voted_users, cast_total_facebook_likes, 
  facenumber_in_poster, budget, title_year, aspect_ratio”.


## Data:


- The dataset used in this project was extracted from IMDb website. 
  we traied dataset from Kaggle to match our needs in order. 
  There were 5000 movies with 28 features initially.
  The dataset becomes almost 3000 records with 20 features after we have done some cleaning and feature engineering on the original dataset.
  
  
## Algorithms:

## ● Feature Engineering:

1. Convert categorical features to dummy variables.
2. Subtracting interactive terms in order to make the feature more relevant. that solved the multicolinaerty in the columns.

## ● Models:

- We have explored many regression machine learning models in order to choose the best for our case. 
  The models are linear regression, K-fold linear regression, Polynomial regression, Ridge regression,lasso regression and random forest.
  The data was splitted into 60 percent training, 20 percent validating, and 20 percent testing. The model we selected was polynomial regression with degree 2 and 3 because it shows the best score between all models.


## Best Model: Polynomial regression with degree 2 and 3:

- Polynomial Training Score: 0.54368493 - Polynomial Testing score: 0.53247904


## Tools:

## ● Technologies:

- Jupyter Notebook, google colab, spyder, Python.

## ● Libraries:

- Pandas, NumPy, Matplotlib, Seaborn, Request, BeautifulSoup, plotly, patsy, holoviews, hvplot, and Sklearn.


## Communication:

<img width="820" alt="Screen Shot 2021-12-11 at 1 20 26 AM" src="https://user-images.githubusercontent.com/58592557/145648748-94dee364-dbd7-4046-8f6a-ec58973aff8e.png">

<img width="474" alt="Screen Shot 2021-12-08 at 10 26 34 PM" src="https://user-images.githubusercontent.com/58592557/145648877-e57e6d2c-3987-4649-895e-6664db9031c1.png">

<img width="228" alt="Screen Shot 2021-12-11 at 1 29 37 AM" src="https://user-images.githubusercontent.com/58592557/145650401-93763ae1-c092-4100-9142-80e0ad816ee6.png">

