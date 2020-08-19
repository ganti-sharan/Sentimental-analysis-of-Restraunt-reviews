# Sentimental-analysis-of-Restraunt-reviews
First we start by cleaning the text: 
  1 . Removing punctuation from the reviews
  2 . Now we convert all the reviews into lower case and split them
  3 . Using PorterStemmer words loved , liked are converted to love , line etc..
  4 .  Stop words are removed
  5 . using count vectorizer we create bagofwords for the data
Now we split the data using test_train_split and Random Forest classifier is used.
