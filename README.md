# Finger food sentiment analysis

A repository with assignment

Selected assignment: 3 (predict score from text descriptions)

### How to use notebooks

- **Dataset-loading.ipynb** :loads data from fingerfood.txt
- **Dataset-cleaning.ipynb** : cleans dataset and prepares partialy for modelling, a bit of EDA
- Analyses
  - Sentiment_analysis-embedding.ipynb - uses keras and NN to encode text and to estimate the score
  - Tfidf.ipyng - uses Tf-idf for ebmedding text and SVC and MultinomialNaiveBayes for the score estimation
  - RandomForest.ipynb - uses bi-grams for embedding and RandomForests with grid search for estimation
  
`./relevant_resources.txt` includes blog posts I used for creation of these notebooks.
