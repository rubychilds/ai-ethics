# [AllenNLP](https://allennlp.org/interpret)

Open source python library. Models built over Pytorch framework, includes numerous pretrained models (e.g. Bert / Elmo etc)

How it works:

- Model Interpretations
  - [Simple Gradients Visualization](https://arxiv.org/abs/1312.6034): Gradient with respect to input text
  - [Integrated Gradients Visualisation](https://arxiv.org/abs/1703.01365):
  - [SmoothGrad Visualisation](https://arxiv.org/abs/1706.03825):
- Advarsarial attacks
  - Input Reduction: Remove
  - Hotflip
- Mask inputs
  - Query language model with masked inputs to return predicted outcomes for the masked word.
