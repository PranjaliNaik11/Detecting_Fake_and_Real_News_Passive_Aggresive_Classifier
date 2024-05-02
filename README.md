# Detecting Fake/Real News using TfidfVectorizer and PassiveAggresive Classifier
Fake news represents the news which are usually hoaxes and spreads through social media or any other media.
Many of them contain false or exaggerated claims which may be viralied using alogorithms.

# TfidfVectorizer
Term Frequency: Defined as the number of times a particular word appears in a document. If the number is high then it means that the term appears more than the others in a given document.

Inverse Document Frequency: If certain words appear many times in a document but they also appear in many other documents then they may be irrelevant. IDF measures the significance of a term.

We use TfidfVectorizer to convert a collection of raw documents into a matrix of TF-IDF features.

# PassiveAggresive Classifier
1) They are online learning algorithms.
2) These algorithms remain passive for a correct classification outcome and turn aggresive in case of a miscalculation or adjusting.
3) Its purpose is to make updates that correct the loss, causing very little change in the weight vector.

# Process
We will use sklearn to build a TfidfVectorizer on our dataset. Then we will initialize a PassiveAggresive Classifier to fit the model.
We will use the accuracy score and confusion matrix to see how well our model fares.

