# [Ran-Debias](https://github.com/TimeTraveller-San/RAN-Debias)

Code implementation of [paper](https://arxiv.org/pdf/2006.01938.pdf) outlining new method to identify and change word embeddings.

Type of debias: Post hoc

How it works:

Transform word embedding using lookup of attract/repel word pairings in relation to type of bias. The word embeddings are then retrained optimising for specific pairings whilst preserving semantic relations.
