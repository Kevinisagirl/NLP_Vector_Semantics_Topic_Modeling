# NLP_Vector_Semantics_Topic_Modeling

Please write an iPython notebook that represents words and articles in the Reuters corpus as vectors and clusters the article vectors. Please use the nltk.corpus.reuters "training" documents (as shown in reuters.fileids()) in one (and only one) of the categories 

ship, trade, interest, money-fx, crude

Create a term-document matrix containing a row for every word in the corpus vocabulary and a column for each document, where each entry is the tf-idf score of a word for a document.
Reduce the size of the matrix. Compute the maximum tf-idf score for each word and keep the 500 rows with the top 500 maxima. Did that remove the maximum tf-idf score of any column? Comment. 
Cluster the document vectors into five clusters using an unsupervised algorithm like k-means. Create a 5x5 matrix that compares each cluster to the each of the above five categories, using the Jaccard Index (see below). Comment.
Try clustering the words and comparing those clusters to the categories, too. Comment on the results.
The Jaccard Index compares two sets A and B.
