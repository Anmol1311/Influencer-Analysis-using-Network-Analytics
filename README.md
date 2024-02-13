# Influencer-Analysis-using-Network-Analytics

## Project Overview
In this project, we aim to utilize the tweets activity data of different users to identify the top 20 influencers among all users. We also explore how profits change when an analytical model is employed to identify influencers through a hypothehical scenario.

#### Part-1
We utilized a Kaggle dataset containing tweets data to build a model to predict influencers. Each observation in the dataset describes two individuals A and B. 'Choice' column in each row shows who among A or B are more influential.
Choice = “1” implies A is more influential than B.
Choice = “0” implies B is more influential than A.
Using this dataset, we created analytics models to classify influencers and identified the best predictors of influence.
#### Part-2
We utilised another file containing tweets of different users. We used the influence scores of best model from Part 1 and concepts of network analytics to identify the top 20 influencers.


## Data Sources
CSV files attached

## Tools Used
- Python: For data processing and analysis.
- Libraries: Pandas,Nltk,Gensim NumPy, Scikit-learn, Matplotlib
- Word2Vec vectorizer

## Medium Article
https://medium.com/@agrawalanmol4273/navigating-the-cinematic-universe-introducing-the-two-way-movie-recommender-system-0dc79ebe59d6
