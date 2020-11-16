# US-Sentiment-Analysis
This data was posted by kolaveridi and includes tweets about 6 major US airlines. Extract the sentiment from the tweet as well as what the passenger was dissapointed about if the tweet was negative.  I used RandomForestClassifier to Classify the Sentiment of the user into Postive , Negtive and Neutral

# Python Libraries used

jupyter , 
numpy ,
pandas ,
re ,
nltk ,
matplotlib ,
seaborn ,
sklearn
install it with : 

pip install -r libraries.txt

# Model Creation
 * Start Jupyter notebook data_cleaning.ipynb
 
# Data Cleaning 

* Remove all the special characters
* remove all single characters
* Remove single characters from the start
* Substituting multiple spaces with single space
* Removing prefixed 'b'
* Convert to lower case

# Represent text the numerical form

 import nltk
 nltk.download('stopwords')
 
 the approach i used to convert the text is TF-IDF , there is many approaches you can use like bag of words, word2vec , doc2vec for docs,... it depends on your case of use
 
 # Splitting data into Training and Test sets

The training set will be used to train the algorithm while the test set to evaluate the performance of the machine learning model.

# Training the model

Random Forest algorithm is used to train the model as it is able to act upon non-normalized data.

# Evaluating the model
Evaluate the performance of the model against test labels using classification metrics

*Confusion matrix
*Classification report
*Accuracy score

# Classiers 

there are many classifiers to test to get better accuracy : 

*Logistic regression
*SVM
*KNN
