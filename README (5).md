
# Twitter Sentiments Analysis

This project focuses on analyzing the sentiment of tweets using a Random Forest Classifier. By leveraging machine learning techniques, the model categorizes tweets into positive, negative, or neutral sentiments based on their content. The project involves data preprocessing, feature extraction, and the application of a Random Forest Classifier to achieve accurate sentiment predictions. This tool can be used to gauge public opinion, monitor brand sentiment, or analyze social media trends.




## Dataset Link

https://raw.githubusercontent.com/laxmimerit/All-CSV-ML-Data-Files-Download/master/twitter_sentiment.csv

Attributes are as follows

 - **Text:** This column contains the tweets that are to be analyzed.
- **Sentiment:** This column represents the sentiment associated with each tweet. The possible sentiment labels are:

  - **Positive**
  - **Negative**
  - **Neutral**
  - **Irrelevant**


  
  

## Model Performance

The Random Forest Classifier used in this Twitter Sentiment Analysis project achieved the following performance metrics:

- **Overall Accuracy:** 94%
- **Precision, Recall, and F1-Score:**
  - **Irrelevant:** 
    - Precision = 0.98
    - Recall = 0.87
    - F1-Score = 0.92
  - **Negative:** 
    - Precision = 0.92
    - Recall = 0.96
    - F1-Score = 0.94
  - **Neutral:** 
    - Precision = 0.95
    - Recall = 0.93
    - F1-Score = 0.94
  - **Positive:** 
    - Precision = 0.91
    - Recall = 0.95
    - F1-Score = 0.93



These metrics demonstrate the model's strong performance across different sentiment categories, with high accuracy and balanced precision, recall, and F1-scores.

