# Sentiment Analysis of Movie Reviews

This project focuses on sentiment analysis of movie reviews using machine learning techniques. It aims to predict whether a movie review expresses a positive or negative sentiment. The project includes exploratory data analysis, data preprocessing, building initial and improved machine learning models, and drawing conclusions based on the results.

## Dataset
The dataset used for this project is the IMDB Movie Reviews dataset. It consists of 50,000 movie reviews, evenly split between positive and negative sentiments. The dataset provides labeled text reviews, which serve as the basis for training and evaluating the machine learning models.

The dataset can be found at the following link: [IMDB Movie Reviews Dataset](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Exploratory Data Analysis (EDA)
The EDA process involved analyzing the dataset to gain insights into the distribution and characteristics of the movie reviews. Some key findings from the EDA process include:
- The dataset contains 25,000 positive and 25,000 negative reviews.
- The average review length for negative sentiment is 229.46456, while for positive sentiment, it is 232.84932.

## Data Preprocessing
Before building the machine learning models, the dataset underwent preprocessing steps to clean and transform the raw text data. The preprocessing steps included:
- Removing HTML tags and special characters.
- Converting text to lowercase.
- Removing stop words.
- Lemmatizing the words.

## Initial Model
The initial model used logistic regression and the CountVectorizer technique for feature extraction. The model achieved an accuracy of 87.98% on the testing set. This model served as a baseline for comparison with subsequent improvement attempts.

## Improvement Attempts
Two improvement attempts were made to enhance the model's performance:

1. Improved Model 1:
   - Linear Support Vector Classifier (LinearSVC) and TfidfVectorizer were used for feature extraction.
   - This model achieved an accuracy of 89.36% on the testing set.

2. Improved Model 2:
   - Grid search was performed to tune hyperparameters, exploring different n-gram ranges and regularization values.
   - The best model obtained from the grid search was used, which achieved an accuracy of 91% on the testing set.

The improved models demonstrated higher accuracy and better performance compared to the initial model.

## Conclusion
In conclusion, this project successfully built machine learning models to predict sentiment in movie reviews. The models demonstrated good performance, achieving accuracy scores between 87.98% and 91% on the testing set. The preprocessing steps and feature extraction techniques played a crucial role in improving the models' performance.

This project showcases the application of machine learning in sentiment analysis and highlights the importance of data preprocessing and feature selection for achieving accurate predictions. It provides a foundation for further exploration and improvement in sentiment analysis tasks.
