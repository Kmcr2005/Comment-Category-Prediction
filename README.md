# Comment-Category-Prediction
This project focuses on multi-class text classification using Natural Language Processing (NLP) and ensemble machine learning techniques. The dataset was preprocessed using text cleaning, stopword removal, and TF-IDF vectorization with uni-grams, bi-grams, and tri-grams to capture contextual information from text data.

Comprehensive Exploratory Data Analysis (EDA) was performed, including label distribution analysis, text length statistics, word frequency analysis, TF-IDF feature importance, correlation analysis, and class-wise text pattern visualization to better understand the dataset and improve feature engineering.

Several machine learning models including Logistic Regression, XGBoost, LightGBM, and SGD Classifier were trained and evaluated. To improve overall performance, a soft Voting Classifier combining Logistic Regression and LightGBM was implemented. Class imbalance was handled using weighted learning techniques, and models were evaluated using F1-score, precision, recall, accuracy, and confusion matrix analysis.

## Tech Stack
- Python
- Scikit-learn
- XGBoost
- LightGBM
- Pandas & NumPy
- Matplotlib & Seaborn

## Key Features
- NLP-focused Exploratory Data Analysis (EDA)
- Advanced text preprocessing pipeline
- TF-IDF feature extraction with n-grams
- Multi-class text classification
- Ensemble learning using Voting Classifier
- Imbalance-aware model training
- Optimized for sparse high-dimensional text data
