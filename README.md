# Sentiment_Analysis_Movie_Reviews

![alt text](https://github.com/arorachinar/Sentiment_Analysis_Movie_Reviews/blob/master/sentiment.png)

In this project, I have done sentiment analysis of movies reviews using SVM for model building NLTK for data pre processing.
The dataset is comprised of tab-separated files with phrases from the dataset. Each Sentence has been parsed into many phrases by the Stanford parser. Each phrase has a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as short/common words) are only included once in the data.

train.tsv contains the phrases and their associated sentiment labels. A SentenceId is used to track which phrases belong to a single sentence.
test.tsv contains just phrases. The task is to assign a sentiment label to each phrase.

The sentiment labels are:

0 - negative
1 - somewhat negative
2 - neutral
3 - somewhat positive
4 - positive
