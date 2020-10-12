# Building and Deploying a Sentiment Analysis Model using AWS SageMaker
### by Abdelrahman Mohammed


### Overview
During this projects, I built a Sentimer analysis model to classify users' moview reviews and find out whether user liked the movie or not. This is a binary classification problem, I used pytorch to build an RNN model.<br><br>

Furthermore, I use AWS SageMaker to build and Deploy the model. Lambda function to configure communication with the created endpoint, and AWS API gateway to access that endpoint. Finally I use a simple web app to communicate with the model.


### Data Set

I use **Large Movie Reviews Data Set** [Link](http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz)<br>
To preprocess data, I use *Bag-of-words* Feature Representation. 

### Accuracy

The model achieves 85% **Test Accuracy**



# Requirements

Download Data set from [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv)

Jupyter notebook must be installed.<br>
Python must be installed. The following python modules must be installed.<br>
```
jupyter
Pytorch
AWS SageMaker
numpy
matplotlib
Pandas
```
