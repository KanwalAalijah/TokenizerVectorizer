# TokenizerVectorizer


### Terminologies:

1) **Tokenizer** Given a character sequence and a defined document unit, tokenization is the task of chopping it up into pieces, called tokens , 
     perhaps at the same time throwing away certain characters, such as punctuation. hese tokens are often loosely referred to as terms or words, but it is              sometimes important to make a type/token distinction. A token is an instance of a sequence of characters in some particular document that are grouped together      as a useful semantic unit for processing. A type is the class of all tokens containing the same character sequence. A term is a (perhaps normalized) type that      is included in the IR system's dictionary. The set of index terms could be entirely distinct from the tokens, for instance, they could be semantic identifiers      in a taxonomy, but in practice in modern IR systems they are strongly related to the tokens in the document. 
     
       
2) **Vectorizer** 
     Documents and queries are represented as vectors.
     Each dimension corresponds to a separate term. If a term occurs in the document, its value in the vector is non-zero. Several different ways of computing these      values, also known as (term) weights, have been developed. One of the best known schemes is tf-idf weighting (see the example below).
     The definition of term depends on the application. Typically terms are single words, keywords, or longer phrases. If words are chosen to be the terms, the          dimensionality of the vector is the number of words in the vocabulary (the number of distinct words occurring in the corpus).
     Vector operations can be used to compare documents with queries.
