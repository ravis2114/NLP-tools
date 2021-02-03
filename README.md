# NLP -Tools
----

- Basics of NLTK
- Tokenization (Sentense & Word)
- Stemming
- Lemmatization

### Word Vectorization Technique [NLP Tools][link1]
----
- Bag of Words (Scikit-Learn Implemetation)
![BOW](https://cutt.ly/fkfUH9z)
- TFidf(Scikit-Learn Implementation)
![TFidf](https://cutt.ly/lkfUIno)
_(term frequency is normalized here)_

### Custom Word Embedding [Custom_Word_Embedding][link2]
----
Steps :
1. Make a corpus of unique words based on their frequency
2. Choose the number of Word Vocabulary (this will be dimension of each words words)
3. Based on Vocab, One_Hot encode every word in a sentence. if this is done using **tf.keras**, a list of dictionary keys will be created which will denote the hot place of that word in word vocab.
4. Make each sentence of equal length by Padding. this can be achieved through **pad_sequences** in **tf.keras**.
5. Create an Embedding Layer with any dimensions of your choice.
6. Input of embedding layer will be _vocab_size_, _embedding_length_ and _length of sentence_.


License
----
MIT


[link1]: <https://github.com/ravis2114/NLP-tools/blob/master/NLP%20TooLs.ipynb>
[link2]: <https://github.com/ravis2114/NLP-tools/blob/master/custom_word_embedding.ipynb>
