#  Recommendations on MovieLens Data Set with TensorFlow and WALS

Hi! I've built a recommender system to recommend movies which is not discovered yet to user. To do this, I've worked on MovieLens data set. I've used TensorFlow framework to implement Weighted Alternating Least Squares algorithm. WALS is one of the well-known Collaborative-Filtering algorithms.

# Dataset:
I've used 100k movie-rating data set from MovieLens.
[https://grouplens.org/datasets/movielens/](https://grouplens.org/datasets/movielens/)

# Guides to build the recommender system:
This project is mixed of these two projects. The first part, reading and analyzing data, is taken from: 
[https://www.analyticsvidhya.com/blog/2018/06/comprehensive-guide-recommendation-engine-python/](https://www.analyticsvidhya.com/blog/2018/06/comprehensive-guide-recommendation-engine-python/)
The second part, implementing WALS, is taken from:
[https://github.com/GoogleCloudPlatform/tensorflow-recommendation-wals](https://github.com/GoogleCloudPlatform/tensorflow-recommendation-wals)

# Lectures to understand recommender systems better:
Before I implemented the recommender system, I finished these two courses respectively:
[https://developers.google.com/machine-learning/recommendation/](https://developers.google.com/machine-learning/recommendation/)
[https://www.coursera.org/learn/recommendation-models-gcp/home/welcome](https://www.coursera.org/learn/recommendation-models-gcp/home/welcome)


# Running the code
I worked on Google Co-Lab. So, I uploaded the data to Google Drive and mounted the drive. If you work on Co-Lab, this code is for you. If not, you should comment mounting part out and change the data path. It is really small changes.


# Future work
I'll split the data into two parts, train and test sets. I'll evaluate the success of the system on test set which is not used on training part. 