Approach:

1.Combine the title and content as text.
2.Take the necessary keywords after removing stopwords, punctuations and lemmatizing.
3.Remove the keywords which appear more than 32 times in the whole datasets, thereby removing most common words which do not imply tags.
	The selection of the number 32 is as samee as that of selectionn of "K" in KMeans Clustering.
4.For each keyword, prepared a dictionary with the list of tags appeared along with the same in the datasets.
5.Take the probabilities of each tag for the respective keywords.
6.For those keywords in the test questions, take the tag with the highest probability and return it as Tags for the same.