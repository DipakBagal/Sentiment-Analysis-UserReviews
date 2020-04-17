# Sentiment-Analysis-UserReviews
This repository has a set of problems in the field of text sentiment analysis. 
Using short (Amazon Reviews Data) and the long (IMDB Reviews Data) format text reviews to extract seentiment 

## Dataset: Amazon Customer Reviews 
*work-in-progress, expected to be updated by Late April*

## Dataset: IMDB Movie Reviews
#### About Data:
IMDB Reviews is one of the best known data datasets for sentiment analysis. It comprises a selection of 50,000 highly-polarized long-form movie reviews. The median length of reviews is 175 words. 

#### Project Goal:
The goal is to use (state-of-art) deep learning frameworks such as Bidirectional LSTMs to classify the sentiment with an accuracy of 85% or more. 

#### Project Approach:
Combined advanced deep learning architectures like Bidirectional LSTMs, with some innovative text pre-processing. Used a 100 dimensional (pre-trained) word- embedding (GloVe, Stanford University) to correct mispelled word and as an iput to the deep network.

From a text-preprocessing standpoint, expanded contractions (*won't -> will not*) and de-coded possesives (*chilren's -> children s*) which helped increase the accuracy of the model. 

#### Result Summary:
All the combined techniques worked well in unision. The final model has an accuracy of 84%
