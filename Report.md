

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

<img width="522" alt="Screen Shot 2021-12-11 at 5 58 25 PM" src="https://user-images.githubusercontent.com/58592557/145681178-9e810eda-ee35-48c3-a756-ec29532c79e2.png">

<img width="327" alt="Screen Shot 2021-12-11 at 5 53 20 PM" src="https://user-images.githubusercontent.com/58592557/145681186-6800dfb4-ec3f-4724-ac67-a3a321af5e8d.png">

<img width="483" alt="Screen Shot 2021-12-11 at 5 54 27 PM" src="https://user-images.githubusercontent.com/58592557/145681201-706552f3-75b8-452e-8d0e-8b048dd49f11.png">

<img width="534" alt="Screen Shot 2021-12-11 at 5 53 49 PM" src="https://user-images.githubusercontent.com/58592557/145681209-fc0b2148-6afe-4706-9dbc-6b003763c895.png">

<img width="756" alt="Screen Shot 2021-12-11 at 5 54 54 PM" src="https://user-images.githubusercontent.com/58592557/145681215-d39d3f11-45c0-44f1-9636-4c5b3305fa48.png">



