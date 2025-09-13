Sentiment Analysis with VADER, RoBERTa, and ML Models 

  

Project Overview: 

This project applies multiple sentiment analysis techniques on Amazon product reviews to understand customer emotions and opinions. The analysis combines lexicon-based methods, machine learning, and transformer models to compare performance, accuracy, and interpretability. 

  

Objectives: 

1.Perform sentiment classification (positive, negative, neutral) on customer reviews 

Compare lexicon-based (VADER) vs. deep learning-based (RoBERTa) approaches 

Explore classical ML models (Logistic Regression, Random Forest) 

Evaluate GPT/OpenAI API for sentiment scoring 

Visualize results for deeper insights 

  

Data Description: 

Reviews.csv: Amazon review dataset (sample of 10,000 reviews used for analysis) 

  

Fields include: 

Id – Unique review identifier 

Text – Customer review text 

Score – Rating (1–5 stars) 

  

Tech Stack: 

Programming: Python 

Libraries: Pandas, NumPy, NLTK, Transformers, Torch, Scikit-learn, Gensim, Seaborn, Matplotlib, OpenAI API 

Environment: Jupyter Notebook / Python Script 

  

Key Features: 

Data Preprocessing: Cleaning, tokenization, POS tagging, NER using NLTK 

Lexicon-based: VADER sentiment analysis (compound, pos, neg, neu scores) 

Transformer-based: RoBERTa (cardiffnlp/twitter-roberta-base-sentiment) for context-aware sentiment scoring 

  

Classical ML: 

Logistic Regression with Doc2Vec embeddings 

Random Forest with TF-IDF features 

GPT/OpenAI API: API-based sentiment scoring for comparison 

Visualization: Correlation heatmaps, KDE plots, bar charts, pairplots 

  

Results & Insights: 

VADER: Fast and interpretable but lacks contextual understanding 

RoBERTa: More accurate and nuanced; best at capturing context but slower 

Logistic Regression & Random Forest: Performed reasonably well; useful as lightweight alternatives 

GPT/OpenAI: Flexible but less consistent than RoBERTa on large-scale text 

Overall: RoBERTa outperformed other models, while VADER remained useful for quick baseline analysis 

  

Future Work: 

Use GPU acceleration for large datasets 

Expand to multilingual sentiment analysis 

Build real-time sentiment dashboards 

Address bias and ethical concerns in sentiment classification 

Authors: 
Shradha Reddy Pulla 
