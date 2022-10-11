# applied-text-mining-in-python
Coursera - Applied Text Mining in Python course assignments and practise exercises.
- Assignment 1

  Used Regex to correctly identify all of the different date variants encoded in this dataset and to properly normalize and sort the dates.
- Assignment 2

  Used nltk to explore the Herman Melville novel Moby Dick.
  - `FreqDist`, `word_tokenize`, `sent_tokenize`, `pos_tag`, `WordNetLemmatizer`
  
  Created three different spelling recommender functions that use nltk to find words similar to the misspelling.
  The distance metrics were:
   -  Jaccard distance on the trigrams of the two words.
   -  Jaccard distance on the 4-grams of the two words.
   -  Edit distance on the two words with transpositions.
  
 - Assignment 3
 
    Explored text message data and create models to predict if a message is spam or not.
    - Fited and Transformed the data usin `CountVectorizer` and `TfidfVectorizer`
    - Fited a multinomial Naive Bayes classifier model to the data `MultinomialNB` , `SVC`, and `LogisticRegression`.
