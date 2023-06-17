# News-article-classification

News Article Classification Model is a machine learning model that classifies news articles into various categories - business, tech, politics, sports and entertainment using Natural Language Processing (NLP).

## Models

The models used are:-
- Logistic Regression
- Random Forest
- Multinomial Naive Bayes
- Support Vector Classifier
- Decision Tree Classifier
- K Nearest Neighbour
- Gaussian Naive Bayes.

## Python Libraries
 
 Download these libraries using pip if haven't already:-
- Natural Language Toolkit
- Regular Expressions
- Numpy
- Pandas
- Matplotlib
- Wordcloud
- Scikit-Learn

## Dataset

- The dataset [News.csv](https://github.com/Riddhi9570/News-article-classification/blob/main/News.csv) comprises of 1490 news articles.
- It contains three columns - ArticleId, Text and Category(business/tech/politics/sports/entertainment).
- 30% of dataset is split for test set and the remaining is used for training.

### Data Visualization in Numeric form:-

![image](https://github.com/Riddhi9570/News-article-classification/assets/72887868/5dd373e7-5c51-48d1-aeaf-f9919de56220)

### Data Visualization in Percentage form:-

![image](https://github.com/Riddhi9570/News-article-classification/assets/72887868/655cbe84-d9c5-480c-87e7-fd729355f9b0)

### Visualizing Category Related Words:-

Business Related Words:-

![image](https://github.com/Riddhi9570/News-article-classification/assets/72887868/7f532109-c772-4350-8bf3-62e325b55266)

Tech Related Words:-

![image](https://github.com/Riddhi9570/News-article-classification/assets/72887868/916f74dc-1454-467f-bece-bc3fbfdbb6fb)

Politics Related Words:-

![image](https://github.com/Riddhi9570/News-article-classification/assets/72887868/1ea04d15-33c6-4943-aa80-455d9b5aa346)

Sports Related Words:-

![image](https://github.com/Riddhi9570/News-article-classification/assets/72887868/d72afe40-d773-4461-bfe8-28ff5abda7e6)

Entertainment Related Words:-

![image](https://github.com/Riddhi9570/News-article-classification/assets/72887868/1a0fc73e-c05e-493f-957c-fb695b3b899a)

## Data Pre-processing

- Removal of tags.
- Removal of special characters.
- Conversion to lower case.
- Removal of stop-words.
- Lemmatizing the Words

## Accuracy

- Accuracy, Precision, Recall and F1 score is displayed for each model.

![image](https://github.com/Riddhi9570/News-article-classification/assets/72887868/ed41d666-eefe-432f-b153-f5a08e1364e0)

- The best accuracy of model is 97.99 from Random Forest.
