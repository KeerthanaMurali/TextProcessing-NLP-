# TextProcessing-NLTK-Python

This project measured the understanding of basic text file processing techniques in the Python programming language. The main outcomes achieved while applying these techniques were:

# Downloading pdf files into text files
Using parallel processing, downloading 200 pdf files from given url's using requests method.

# Segmentation, Tokenization, collocation extraction.
By using the punkt package breaking the total string into sentences. Using re package tokenizing the segmented sentences. From the combined unigram tokens of all documents, we have to extract the top 200 bigrams. 200 bigrams were generated to further tokenize the initial nltk corpus. The PMI measure was used to detect pairs of words with high probability of appearing together. In addition, bigram filters were also used to refine the bigrams even more.

# Vocabulary and sparse vector generation.
A vocabulary covering words from different documents was obtained by removing stop words, the words which have threshold greater than 95% and less than 3%. Inorder to get the frequency count of each word pd.Series dataframe is used with value_counts function. The sparse vector is generated based on the index value of sparse vocabulary list as key and its frequency in the particular document as value.
