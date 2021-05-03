# Naive Machine Translation and LSH
Implement  machine translation system and then see how locality sensitive hashing works.In this project we translate from english to french using word vectors and find similarity b/w both vectors. For this we use **English embeddings from Google code archive word2vec** and **French embeddings from cross_lingual_text_classification** and also used **english to french word mapping** to train and test our model from scratch. After this we develop a **Locality Sensitive hashing** for searching documents effeciently from a large set. We implement that on tweets data set for grouping similer tweets using **Locality Sensitive hashing**

We can devide it in Some parts :

* Part 0 : Import useful package
* Part 1 : Load the data and process it
  * Generate embedding and transform matrices
* Part 2 : Translations
  * Translation as linear transformation of embeddings
  * Testing the translation
* Part 3 : LSH and document search 
  * Getting the document embeddings
  * Looking up the tweets
  * Finding the most similar tweets with LSH
  * Getting the hash number for a vector
  * Creating a hash table
  * Creating all hash tables

We get accuracy on translation is `55.70%`.

