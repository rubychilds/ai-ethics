# [DebiasWe](https://github.com/tolga-b/debiaswe)

This is the code of the research [paper](http://papers.nips.cc/paper/6228-man-is-to-computer-programmer-as-woman-is-to-homemaker-debiasing-word-embeddings.pdf) “Man is to computer programmer as woman is to homemaker” which was one of the first papers in the space.

Cons

- No setup.py or requirements.txt
- Not actively maintained, last commit in Apr 2018
- Binary format is not the only format used for word embeddings
- Works on gender though it can possibly generalise

Pros

- It received a generic format of word embeddings and produces a debiased version in the same format so in theory it can be used for exactly that use case relatively easily

Type of debias: Post hoc

How to use

You need to provide

- word embeddings in binary format .bin
- definitional pairs for gender used to define direction for gender
- equalise pairs used to ensure only difference between some words are gender

## [Sent debias](https://github.com/pliang279/sent_debias)

Yet another code from a [paper](http://www.cs.cmu.edu/~pliang/papers/acl2020_debiasing.pdf). This extend debiasing to context dependent embeddings.

Type of debias: Post hoc

How it works:

The produce sentence embeddings given a diverse sentence template scheme where the substitute the sensitive words into a fixed template. Then
