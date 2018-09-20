# pytorch-word2vec
Model is located in word2vec.ipynb.

Pytorch implementation of word2vec. Word2Vec uses a neural network to create word embeddings from a corpus of words. The embeddings are created based on proximity (words that are closer together are assumed to have similar meanings). 

Currently the embeddings do not seem to demonstrate word meanings. Next steps are to:
* Get rid of very common / very rare words - these don't actually help to determine the meaning of other words
* Implement negative sampling - don't update all of the word weights each time we run the network because this is very slow and unnecessary 
