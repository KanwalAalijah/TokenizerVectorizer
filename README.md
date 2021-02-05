# TokenizerVectorizer


### Terminologies:

1) **Tokenizer** Given a character sequence and a defined document unit, tokenization is the task of chopping it up into pieces, called tokens , 
     perhaps at the same time throwing away certain characters, such as punctuation. Here is an example of tokenization:
     Input: Friends, Romans, Countrymen, lend me your ears;
Output: \framebox{Friends\weestrut} \framebox{Romans\weestrut} \framebox{Countrymen\weestrut} \framebox{lend\weestrut} \framebox{me\weestrut} \framebox{your\weestrut} \framebox{ears\weestrut}
     
     
     
     
2) **TF** is the number of times a term (word) occurs in a document.  
3) **IDF** is a numerical statistic that is intended to reflect how important a word is to a document.  
4) **Stop Words** are the words which donot contain important significance to the search queries.
5) **MapReduce** is a programming model and an associated implementation for processing and generating large data sets with a parallel, distributed algorithm on a cluster.
6) **Apache Hadoop** is an open-source software framework used for distributed storage and processing of big data sets using the MapReduce programming model.

### Formulas:
TFIDF = n/N * log(D/m)
n is the number of times a word is in a document
N is the sum of all n's of a document
