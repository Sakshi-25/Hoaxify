# Hoaxify
Hoaxify is a Fake News Classifier built using NLP Techniques.

### Dataset

News.csv : A full trained dataset on following attributes-
- news: news article no.
- title: the title of a news article
- text: the text of the article; could be incomplete
- label: a label that marks the article as potentially unreliable. where FAKE: unreliable and REAL: reliable

### Dependencies

- Pyhton 3.x
- NLTK
- NumPy
- Pandas
- sklearn
- CountVectorizer
- TfidfTransformer

### Modelling

I have fit 4 models to the training set, with testing accuracy of the models being:

- Logistic Regression (91.16%)
- Naive Bayes (82.32%)
- Decision Tree (80.49%)
- PassiveAggressive Classifier (93.12%)


