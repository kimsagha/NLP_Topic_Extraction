# NLP Project
## Topic extraction
The purpose of this project is to classify news articles by which topic they belong to via topic extraction.

### Data
- The data set was downloaded from Kaggle at: https://www.kaggle.com/snapcrack/all-the-news?select=articles3.csv
- Data files are tracked by git lfs

#### Documentation
- List all models and their definitions
- Show pre and post processing versions for one selected article
- List the topics resulting from each model for a selected 3 articles
- Explain the reason for not using any supervised models: getting labelled data is infeasible, not relevant, not a challenge for me (similar to sentiment analysis but could’ve extended it with word embeddings instead of bag-of-words)

#### Questions
- What do you do when the word for the topic doesn’t exist in the text?
- LDA/LSA: how do you select the number of topics? Is there a more efficient way than trial-and-error?
- How can I measure the performance of unsupervised models?
- Are NER outputs topics?
- Identify n-grams (or taken into account during tokenization?)? [data_words_bigrams = make_bigrams(data_words_nostops)]



### Model Results
#### LDA
- Coherence score for entire first csv with 20 topics: 0.3538168453269389