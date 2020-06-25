# Movie Rating Prediction: Project Overview:

* Created a tool for predicting the IMDb rating of a movie from a dataset acquired from kaggle.
* Cleaned the data and made it usable for model muilding
* Used supervised machine learning(KNN algorithm) for predicting the IMDb rating.

# Code and Resources Used:
* **Language**: Python
* **Packages**: numpy, pandas, matplotlib, seaborn, sklearn
* **Dataset**: https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney

# Data Cleaning
I made the following changes and created the following variables:
* Dropped all the columns which were not required
* Filled all the missing values appropriatly for each column
* Created different column for each genre
* Seperated data into different dataframes according to their streaming platform for 

# EDA
For better understanding of the dtaset, I looked at the distributions of data and value counts of catagorical data. Below are a few highlights<br>
![Movie Distribution](/images/movie proportion.PNG)

# Model Building and Accuracy Score
* I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.
* I used KNN algorithm with n_neighbours parameter set to 5.
* The model corectly predicted the movie rating with an accuracy of 25.94%
