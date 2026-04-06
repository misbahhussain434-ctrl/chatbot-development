This project implements a Natural Language Processing (NLP) pipeline for analyzing the sentiment of textual data. The system supports both individual sentiment analysis (single text input) and batch analysis (processing multiple texts at once). The project is designed to help understand the emotional tone of text, useful for social media monitoring, customer feedback analysis, and more.

Features:

Sentiment Classification: Categorizes text as Positive, Negative, or Neutral.
Batch Analysis: Allows processing multiple texts from a CSV or text file in one run.
Preprocessing: Cleans text data by removing punctuation, stopwords, and special characters.
Visualizations: Optional charts showing sentiment distribution for batch data.
Flexible Input: Accepts input from files or direct user input.
Technologies Used
Programming Language: Python 3.x

Libraries & Tools:

nltk – Natural Language Toolkit for preprocessing
scikit-learn – For model training and evaluation
pandas – Handling tabular data for batch analysis
matplotlib / seaborn – For visualizations
joblib – Save/load trained models
