# Twitter Sentimental Analysis
### Sentiment analysis on 1.6 milion tweets

- Find the dataset here: https://www.kaggle.com/karan842/twitter-sentimental-analysis/data 

 ## 🔵 About Project
 Twitter is one of the most famous social media platform on which we can share our thoughts, opinion and trending related tweets in the form of text, images and videos. In this task I am going to analyze sentiments of tweets which are in the form of tweets.
 I collected this data from **Kaggle**. As the task is depeneded on tweets which texts so this is a problem of **Natural Languages Processing**. There are 1.6 milion tweets in this data so dataset is very huge.
 Main task is to predict sentiments behind tweeet that means, is tweet is positive? or negative? By this strategy we can find good or bad tweets I mean which tweets are harmful and disrespectful according to Twitter guidlines.
 

##  Approach:
1. Collected data from Kaggle
2. Imported with essential steps and created a visual that describes number of positive and negative tweets.
3. Text Processing:  steps taken are Lower Casing,
                     - Replacing Emojis,
                     - Replacing Usernames,
                     - Removing Non-Alphabets,
                     - Removing Consecutive letters,
                     - Removing Short Words,
                     - Removing Stopwords,
                     - Lemmatizing.
4. For this project I am using **NLTK** library. You can use spaCy3 or other.
5. By WordCloud I displayed important words from negative and positive tweets.
6. Splitted a data into training and testing data.
7. Created 3 different types of model for better results and accuracy: Bernoulli Naive Baye(Bernoulli)
Linear Support Vector Classification (LinearSVC)
Logistic Regression (LR).
8. Evaluated 3 models by classification report and confusion matrix.
9. Select best model among them.
10. Saved the models
11. Write a function which can predict sentiment of tweets.
12. Took some sentences and found their sentiments.


## Thank You!
 
