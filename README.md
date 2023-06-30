# AASD 4011 - Mathematical Concepts for Deep Learning Project Proposal

## Members: 

1. Michelle Ohikhena (101428168) 
2. Megi Xhafka (101445718)

## Topic

***Fine-tuning LSTM Model for Sentiment Analysis on IMDb Movie Reviews: Exploring the Impact of Weight Initializers and Optimizers***

## Problem statement

Sentiment analysis plays a crucial role in understanding public opinion and feedback. By exploring and ***comparing*** different ***weight initializers*** and ***optimizers***, we can gain insights into how these hyperparameters affect the performance of the LSTM model for sentiment analysis on the IMDb dataset. The analysis will provide valuable information on which combinations of weight initializers and optimizers yield the best results, enabling us to make informed decisions for model selection and fine-tuning.

## Dataset

The link to the dataset found on kaggle is: [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?sele=&select=IMDB+Dataset.csv) which contains 50,000 reviews.

## Methodology

1. We will explore the dataset to gain insights into the distribution of sentiment labels, the length of the text, and any patterns or trends that may be present, then preprocess the text data by: 

    - removing HTML tags, punctuation, stopwords
    - converting the text to lowercase
    - apply tokenization
    - padding
    - etc.

2. We will divide the dataset into a training set and a testing set, using an 80-20 split. The training set will be used for training the LSTM model, while the testing set will be used for evaluating the model's performance.

3. We will define the LSTM model architecture for binary sentiment classification. 

4. We will explore the impact of different weight initializers and optimizers on the performance of the LSTM model for sentiment analysis on the IMDb dataset. Specifically, we will experiment with the following weight initializers:

    1. Glorot Uniform Initialization
    2. Glorot Normal Initialization
    3. He Uniform Initialization
    4. He Normal Initialization
    5. LeCun Normal Initialization

    and different optimizers such as:

    1. Adam
    2. SGD (Stochastic Gradient Descent)


5. For evaluation, we will use metrics such as ***accuracy*** to assess the model's performance in sentiment classification. 

## Conclusion 

At the end of the project we are expected to get different accuracies and we will conclude which combination of weight initializer and optimizer is better for sentiment analysis on the IMDb movie review dataset.

## References 

Helper codes will be taken from these websites:
- [Layer weight initializers](https://keras.io/api/layers/initializers/#randomnormal-class)
- [LecunNormal](https://www.tensorflow.org/api_docs/python/tf/keras/initializers/LecunNormal)
- [Optimizers](https://keras.io/api/optimizers/)
- [ChatGPT](https://chat.openai.com/)
