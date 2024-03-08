# Natural-Language-Processing
## NLP pipeline:
1. **Text Preprocessing Level 1:** Tokenization,Lemmatization,StopWords,POS
2. **Text Preprocessing Level 2:** Bag Of  Words, TFIDF, Unigrams,Bigrams,n-grams
3. **Text Preprocessing:** Gensim,Word2vec,AvgWord2vec
4. Solve Machine Learning Usecases
5. Understanding Recurrent Neural Networks, LSTM,GRU
6. **Text Preprocessing Level 3:** Word Embeddings, Word2vec
7. Solve DL usecases
8. Bidirectional LSTM RNN, Encoders And Decoders, Attention Models
9. Transformers
10. BERT

## Text Preprocessing Level 1 
**Tokenization:** Tokenization is a process in NLP where we break down a text into smaller chunks called tokens. These tokens can be individual words, phrases, or even characters, depending on how we define them. <br>Example: Imagine you have a sentence: "The quick brown fox jumps over the lazy dog." Tokenizing this sentence would break it down into individual words: "The", "quick", "brown", "fox", "jumps", "over", "the", "lazy", "dog".<br>
**Implemention in python libraries (nltk and spaCy):**
1. **Word Tokenization:** This method splits text into individual words or tokens.
```python
import nltk
from nltk.tokenize import word_tokenize

#Sentence to tokenize
sentence = "The quick brown fox jumps over the lazy dog."

#Tokenize the sentence
tokens = word_tokenize(sentence)

#Print the tokens
print(tokens)
```
This code will output
```python
['The', 'quick', 'brown', 'fox', 'jumps', 'over', 'the', 'lazy', 'dog', '.']
```
3. **Sentence Tokenization:** This method splits text into individual sentences.
4. **Whitespace Tokenization:** This method splits text based on whitespace characters (space, tab, newline).
5. **Regexp Tokenization:** This method uses regular expressions to define the tokenization pattern.














