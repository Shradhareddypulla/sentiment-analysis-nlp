Sentiment Analysis with VADER, RoBERTa, and ML Models 

  

Project Overview: 

This project applies multiple sentiment analysis techniques on Amazon product reviews to understand customer emotions and opinions. The analysis combines lexicon-based methods, machine learning, and transformer models to compare performance, accuracy, and interpretability. 

  

Objectives: 

1.Perform sentiment classification (positive, negative, neutral) on customer reviews 

2.Compare lexicon-based (VADER) vs. deep learning-based (RoBERTa) approaches 

3.Explore classical ML models (Logistic Regression, Random Forest) 

4.Evaluate GPT/OpenAI API for sentiment scoring 

5.Visualize results for deeper insights 

  

Data Description: 

Reviews.csv: Amazon review dataset (sample of 10,000 reviews used for analysis) 

  

Fields include: 

1.Id – Unique review identifier 

2.Text – Customer review text 

3.Score – Rating (1–5 stars) 

  

Tech Stack: 

1.Programming: Python 

2.Libraries: Pandas, NumPy, NLTK, Transformers, Torch, Scikit-learn, Gensim, Seaborn, Matplotlib, OpenAI API 

3.Environment: Jupyter Notebook / Python Script 

  

Key Features: 

1.Data Preprocessing: Cleaning, tokenization, POS tagging, NER using NLTK 

2.Lexicon-based: VADER sentiment analysis (compound, pos, neg, neu scores) 

3.Transformer-based: RoBERTa (cardiffnlp/twitter-roberta-base-sentiment) for context-aware sentiment scoring 

  

Classical ML: 

1.Logistic Regression with Doc2Vec embeddings 

2.Random Forest with TF-IDF features 

3.GPT/OpenAI API: API-based sentiment scoring for comparison 

4.Visualization: Correlation heatmaps, KDE plots, bar charts, pairplots 

  

Results & Insights: 

1.VADER: Fast and interpretable but lacks contextual understanding 

2.RoBERTa: More accurate and nuanced; best at capturing context but slower 

3.Logistic Regression & Random Forest: Performed reasonably well; useful as lightweight alternatives 

4.GPT/OpenAI: Flexible but less consistent than RoBERTa on large-scale text 

5.Overall: RoBERTa outperformed other models, while VADER remained useful for quick baseline analysis 

  

Future Work: 

1.Use GPU acceleration for large datasets 

2.Expand to multilingual sentiment analysis 

3.Build real-time sentiment dashboards 

4.Address bias and ethical concerns in sentiment classification 

Authors: 
Shradha Reddy Pulla 
