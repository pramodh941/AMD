# AMD

#Code executed in Google Colab
#Need to upload your Kaggle json file hence to pull the dataset from Kaggle

#Description:
#Cleaned data (removed unnecessary string,code patterns, stopwords
#Tokenized the questions
#Implemented TfIdf to extract feature vectors (of 8 vectors each)
#Feature vectors passed to MinHashLSH (of 5 buckets)
#Used "approxnearestNeighbours" to group similar questions
