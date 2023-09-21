# FakeNewsDetection
writing python code to detect the fake news based upon the frequency of certain words in the news.
It uses NLP's tfidftransformer for determining the frequency of words and based on that it will detect the Fake news.
First of all i have used https://www.kaggle.com/datasets/ahmedsayed564/fake-news-detection dataset for training the model
After collecting data the content of the news is passed through pipeline first containing CountVectorizer then tfidftransformer and the multinominal naive bayes.
With Tfidftransformer we will systematically compute word counts using CountVectorizer and then compute the Inverse Document Frequency (IDF) values and only then compute the Tf-idf scores.
After the model is formned it will give accuracy of 93.54%
