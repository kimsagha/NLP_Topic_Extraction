# NLP Project
## Topic extraction
The purpose of this project is to classify news articles by which topic they belong to via topic extraction.

### Data
- The data set was downloaded from Kaggle at: https://www.kaggle.com/snapcrack/all-the-news?select=articles3.csv
- Data files are tracked by git lfs

#### Documentation
- List all models and what defines them
- List the topics resulting from each model for a selected 3 articles for which I’ll show pre and post processed versions too
- Explain the reason for not using supervised models: getting labelled data is infeasible, not relevant, not a challenge for me (similar to sentiment analysis but could’ve extended it with word embeddings instead of bow)

#### Questions
- What do you do when the word for the topic doesn’t exist in the text?
- LDA/LSA: how do you select the number of topics? Is there a more efficient way than trial-and-error?
- How can I measure the performance of unsupervised models?