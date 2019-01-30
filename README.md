# understanding-word2vec

Understanding Word2vec architecture and using it to extract dish names from restaurant review corpus.

Best way to understand a paper is through implementing it and using it in a project. 

Here I have used below publications and referenced several other allied publications to deepen my understanding of word2vec. 

T. Mikolov et al., Efficient estimation of word representations in vector space, ICLR 2013

T. Mikolov et al., Distributed Representations of Words and Phrases and their Compositionality, NIPS 2013

## Background
I had previously built a ranking algorithm that ranks restaurants given a dish name using Yelp review corpus.

This project needed dish name extraction from review corpus and hence resorted to word2vec architecture.

I have implemented the w2v architecture (skip-gram version) using naive soft-max method as well as speed optimized negative-sampling method.

The derivations, implementations, and results are documented in the powerpoint along with the code and visualizations.
