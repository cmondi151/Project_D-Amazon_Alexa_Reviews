## Colin Mondi - Kaggle Competition - Amazon Alexa Reviews

### Overview

For this hackathon challenge students were given a single day to pick a tabular dataset and make a predictive model. I decided to do a **sentiment analysis for Amazon Alexa reviews** (Kaggle Competition, link below). The goal was to predict what rating (score of 1 - 5) an individual gave the Alexa they recently purchased using only the content from their written review. The data contains ~3,000 rows, each reflecting an independent review.

Given the short amount of time to complete this, there's a limited amount of cleansing, EDA, pre-processing, and model testing applied in this project in comparison to the other projects in my repository.  

### Models
Model 1: Naive Bayes (MultinomialNB)

Model 2: Logistic Regression

Functions utilized:
- WordNetLemmatizer: return dictionary form of individual word (created new "cleaned" version of the written review column)
- CountVectorizer: determine word frequency 
- TfidfTransformer: determine word relevance

### Conclusion

Both models predicted the correct rating ~70% cases -

- Naive Bayes Model Accuracy Score: 71% correct
- Logistic Regression Model Accuracy Score: 72% correct

----
Kaggle Link: https://www.kaggle.com/sid321axn/amazon-alexa-reviews

