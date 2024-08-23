# Sentiment Analysis of Hotel Reviews
by damarsa (github.com/damarsajiputra)

### Project Overview
This project involves building a sentiment analysis model to classify hotel reviews into three categories: Positive, Neutral, and Negative.

### Dataset
Dataset title : TripAdvisor Hotel Review
source :  https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews/dat


### Project Steps
1. Exploratory Data Analysis (EDA)
        - Performed data visualization to understand the distribution of sentiments.
        - Analyzed common words in each sentiment category.

2. Text Preprocessing
        -Normalize text (Converted text to lowercase; Removed non-alphabetic characters, numbers, and stop words; Applied stemming/lemmatization).

3. Feature Engineering
        -Tokenized the text data.
        -Applied padding to ensure consistent input lengths.
        -Resampled the data to address class imbalance.

4. Model Building
        - Use Tensorflow to Build LSTM Model for classification.
        
5. Evaluation
        - Use Confusion Matrix, Classification Report, ROC Curve, and Precision-Recall Curve.


