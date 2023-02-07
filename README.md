# IOT_Project

By: Jyoti Ramola

Sentiment Analysis of IMDB Movie Reviews

Brief on the project: -

Sentiment analysis of IMDB movie reviews involves using natural language processing and machine learning techniques to determine the sentiment or emotional tone of a piece of text, in this case, a movie review. This can be done by training a model on a dataset of labelled movie reviews (e.g., positive, negative, neutral) and then using that trained model to classify new, unseen reviews. Sentiment analysis can be useful in understanding the overall public opinion about a movie.

Deliverables of the project:-

●	Data Pre-processing :- In this section we aim to do some operations on the dataset before training the model on it, processes like :
a.	Loading the dataset
b.	Load necessary libraries
c.	EDA analysis: This dataset is balanced and split into train and test data.
d.	Data cleaning: Remove HTML tags
e.	Data cleaning: Remove special characters
f.	Data cleaning: Convert everything to lowercase
g.	Data cleaning: Remove stop words
h.	Data cleaning: Stemming.

●	Converting features to BOW and TFIDF vector form.
●	Model Creation: - The dataset is ready for training so we created Logistic Regression, Linear SVM , Multinomial Naïve Bayes, model using scikit learn library and then fit it to the data.
●	Model Evaluation :- Finally we evaluate the model performance on test data,  accuracy, classification report ,confusion matrix .
●	Also checked word cloud for positive and negative sentiments.

Conclusion:

•	We can observe that both logistic regression and multinomial naïve bayes performing well compared to linear SVM.

•	We can also improve the accuracy of the model by using lexicon model text blob etc.


Resources: -

1.	Data set source - https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
2.	Software - Google colab
3.	References - https://www.kaggle.com/code/lakshmi25npathi/sentiment-analysis-of-imdb-movie-reviews/data

