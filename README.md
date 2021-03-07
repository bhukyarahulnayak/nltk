# Lab Task-4: Part-of-Speech (POS) Tagging, Chunking and Named Entity Recognition (NER) using RNN and Bi-LSTM.

In this lab task, 

### File architechure

The main directory consists of THREE directories
- CHUNKING
- POS
- NER

### CHUNKING

- I have implemented CBOW embedding using gensim from the python library. For this I have loaded my training data into a variable and performed all the text preprocessing on the training dataset
- Next, I have tokenized all the sentences and removed the stopwords from the sentences 
- Then words are been tokenized and finally fed to the model
- model is created using the Word2vec function which is imported from the gensim.models
- This model has predicted two similar words of same context
- Visulisation plots (PCA and t-SNE) for most similar words as well as the complete embedding space are done

### POS

- Skip-gram embedding is implemented using gensim. 
- Text-Preprocessing and tokenization is done for the training data.
- Then cleaned data is fed to the model.
- This model has predicted two similar words of same context
- Visulisation plots (PCA and t-SNE) for most similar words as well as the complete embedding space are done

### NER

- For Glove Embedding I have loaded a pre-trained model 
- Made few prediction using that model
- Visulisation plots (PCA and t-SNE) for most similar words as well as the complete embedding space are done
