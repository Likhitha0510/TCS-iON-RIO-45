# TCS-iON-RIO-45
Automate detection of different emotions from textual comments and feedback Batch 1

# Project Description:
# Project Objective & Brief:  
To develop a deep learning algorithm to detect different types of emotion contained in a collection of English Sentences or a larger paragraph

# Project Guidelines
1. Identify and finalize a collection of English text,sentences or large paragraphs covering emotions like happy,sad,expressing,love,anger or surprise.
2. Develop a deep learning model for detection & segmentation of emotions contained in the text,sentence or paragraph
3. The above model should also accurately handle scenarios where the following are present
    a. Sarcastic Meaning
    b. Double negation words
    c. Abbreviations like 'nxt','2tmrw','things r gd',etc).
4. Test the model for accuracy.

# Expected Project Outcome

1. Algorithm to detect different types of emotion from a paragraph.
2. Detailed presentation with proof of reasonable accuracy

# Hands on environment details

Hands-on environment or software required to implement the project
1. Google Collab (https://colab.research.google.com)
2. Software required -
   a. Python
   b.Java(optional)
   c. Eclipse
   d. Ubuntu OS(optional)/Virtual box

Approaches to Text Classification
Rule Based Systems:
Rule-based approaches classify text into organized groups by using a set of linguistic rules.
Each rule comprises of a pattern based on semantics and its predicted category.
Machine Learning based Systems:
Text classification based on past observations.
By using training data, the algorithm can learn the different associations between pieces of text and that a particular output (i.e. tags) is expected for a particular input (i.e. text).
Feature extraction: Transforms each text into a numerical representation in the form of a vector. E.g. bag of words [a vector represents the frequency in a predefined dictionary of words ]
The algorithm is fed with training data consisting of feature sets.
Once trained with enough training samples, the machine learning model can begin to make accurate predictions on unseen text with similar feature sets.
Text Classification Algorithms
Some of the most popular machine learning algorithms for creating text classification models include the naive bayes family of algorithms, support vector machines, Regressions, and deep learning algorithms with CNN and RNN. Metrics and Evaluation Cross-validation is a common method to evaluate the performance of a text classifier.

It consists in splitting the training dataset randomly into equal-length sets.
For each set, a text classifier is trained with the remaining samples (e.g. 75% of the samples).
The classifiers make predictions on their respective sets and the results are compared against the human-annotated tags.
With these results, a performance metrics is built, that are useful for a quick assessment on how well a classifier works.
Performance metrics normally includes:
Accuracy: the percentage of texts that were predicted with the correct tag.
Precision: the percentage of examples the classifier got right out of the total number of examples that it predicted for a given tag.
Recall: the percentage of examples the classifier predicted for a given tag out of the total number of examples it should have predicted for that given tag.
F1 Score: the harmonic mean of precision and recall.
Data Sources to solve problem
Data Sets from any open source data sources can be used. Model building and solution engineering is NOT restricted to data.
Example:
https://ai.stanford.edu/~amaas/data/sentiment/ 

https://data.world/crowdflower/sentiment-analysis-in-text

https://www.kaggle.com/crowdflower/twitter-airline-sentiment

Test Accuracy achieved with IMDB dataset :
The accuracy achieved is : 86.67
https://colab.research.google.com/drive/190qSrqHWuefOyyD7j-eaDgJRgYBhlc-u#scrollTo=uqklEKmW7tvk&line=1&uniqifier=1

The accuracy achieved is : 87.28
https://colab.research.google.com/drive/190qSrqHWuefOyyD7j-eaDgJRgYBhlc-u#scrollTo=3ogZeYkv9nfT&line=3&uniqifier=1
