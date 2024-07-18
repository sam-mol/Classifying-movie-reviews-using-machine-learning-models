Binary classification, or two-class classification, is one of the most common problems in data science. In this project, I will classify movie reviews as positive or negative based on the text content of the reviews by training deep learning models.
I will be using Internet Movie Database (IMDB). IMDB dataset has 50,000 highly polarized movie reviews. The reviews are split into 25,000 reviews for training and 25,000 reviews for testing, each dataset containing 50% positive and 50% negative reviews. 
In this project, I will use IMDB dataset that comes with Keras datasets, where it has already been partially preprocessed by turning sequence of words into sequence of integers, where each integer corresponds to a specific word in a predefined dictionary. But we still need to do a fair amount of data preprocessing, we can not feed sequence of integers into deep learning models since the sequences are all of different lengths; we need to turn the sequences into equal size tensors to feed them into a deep learning model. 
If you want to preprocess the raw text input from scratch, you can access the data from the following link, http://ai.stanford.edu/~amaas/data/sentiment/. 

I will use a deep learning framework Keras to implemented a model. Keras is a go-to tool to build deep learning models. 

Here are the steps that comprised the project:
Download the data that has already been split into training and testing sets.
Further clean the data and transform the data into a format that can be accepted by a model.
Build a model.
Train the model using the training dataset and track the model’s performance.
Adjust hyperparameters if needed and train the model again.
Test the model on the test set.
Report the findings.

References:
Keras is well described by its creator François Chollet in his book "Deep Learning with Python". The mechanics of how to preprocess the IMDB dataset to transform the sequences of words into sequences of integers can also be found in the book. 
