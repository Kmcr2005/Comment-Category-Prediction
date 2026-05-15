# Comment-Category-Prediction
This project focuses on multi-class text classification using advanced Natural Language Processing (NLP) and ensemble machine learning techniques. The dataset was preprocessed using text cleaning, stopword removal, and TF-IDF vectorization with uni-grams, bi-grams, and tri-grams to capture contextual information from text data.

Multiple machine learning models including Logistic Regression, XGBoost, LightGBM, and SGD Classifier were trained and evaluated. To improve overall performance, a Soft Voting Classifier ensemble was implemented by combining Logistic Regression and LightGBM models.

The project also includes extensive Exploratory Data Analysis (EDA) such as:

Label distribution analysis
Text length and word count statistics
TF-IDF feature importance analysis
Correlation and multivariate analysis
Most frequent and class-specific word visualization

Class imbalance was addressed using class weights and weighted learning techniques. Model performance was evaluated using F1-score, precision, recall, and confusion matrix analysis.
