## Pros and Cons

<table>
  <tr>
   <td>Tool
   </td>
   <td>Key Pros
   </td>
   <td>Key cons
   </td>
   <td>Open source
   </td>
   <td>Maturity / last edited
   </td>
  </tr>
  <tr>
   <td>Debiaswe <a href="https://github.com/tolga-b/debiaswe">https://github.com/tolga-b/debiaswe</a>
   </td>
   <td>
<ul>

<li>Exposes entry point to debiasing word embeddings in bin format with one line
</li>
</ul>
   </td>
   <td>
<ul>

<li>No setup.py or requirements

<li>Research code

<li>Not actively maintained
</li>
</ul>
   </td>
   <td>Yes
   </td>
   <td>Apr 2018
   </td>
  </tr>
  <tr>
   <td>Sent debias <a href="https://github.com/pliang279/sent_debias">https://github.com/pliang279/sent_debias</a>
   </td>
   <td>
<ul>

<li>Work for contextualised embeddings so BERT / Elmo type

<li>Multi class protected group
</li>
</ul>
   </td>
   <td>
<ul>

<li>No documentation

<li>No setup.py or requirements

<li>Quite difficult to get started

<li>Few commits / stars
</li>
</ul>
   </td>
   <td>Yes
   </td>
   <td>May 2020
   </td>
  </tr>
  <tr>
   <td>AllenNLP Interpret
<p>
<a href="https://allennlp.org/interpret">https://allennlp.org/interpret</a>
   </td>
   <td>
<ol>

<li>Variety of methods to help interpretation of models (Gradientvisualisations and input perturbation)

<li>Released library with software development principles applied(unit tests) & Containerised docker images to easily reuse pre-trained models.

<li>UI front end to look at anecdotal examples on front end. 
</li>
</ol>
   </td>
   <td>
<ol>

<li>Not compatible with models outside of AllenNLP / Pytorch framework (i.e.won’t work with Tensorflow)

<li>Accessibility/setup is more difficult in non-GPU enabled environments. 
</li>
</ol>
   </td>
   <td>Yes
   </td>
   <td>Actively worked on
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/TimeTraveller-San/RAN-Debias">https://github.com/TimeTraveller-San/RAN-Debias</a>
   </td>
   <td>
<ol>

<li>Method implementation helps to fix across multiple associated words(e.g. stereotyped jobs) and to equalise these between biased groups

<li>New measure of Bias (Gender-Based Illicit Proximity Estimate) wrt distance between gender associated words from user input. 
</li>
</ol>
   </td>
   <td>
<ol>

<li>Research Code, not tested, not packaged.

<li>Single method implemented(bespoke)

<li>Assessed only for downstream task of co-reference
</li>
</ol>
   </td>
   <td>Yes
   </td>
   <td>First commit June 2020
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/TManzini/DebiasMulticlassWordEmbedding">https://github.com/TManzini/DebiasMulticlassWordEmbedding</a>
   </td>
   <td>
<ol>

<li>Provides transformed word embeddings wrt to corpus

<li>Output of debiasing assessed on several downstream tasks(NER, POS tagging/chunking) preserving semantic relationship.
</li>
</ol>
   </td>
   <td>
<ol>

<li>Single method of transformation

<li>Not packaged / tested

<li>Method relies on word analogies provided by the user. To retrain from scratch on new corpus would require substantial refactoring.
</li>
</ol>
   </td>
   <td>Yes
   </td>
   <td>June 2019
   </td>
  </tr>
  <tr>
   <td><a href="https://docs.seldon.io/projects/alibi/en/stable/overview/algorithms.html">https://docs.seldon.io/projects/alibi/en/stable/overview/algorithms.html</a>
   </td>
   <td>Explainer
<p>
<a href="https://docs.seldon.io/projects/alibi/en/stable/methods/Anchors.html">Anchors</a>
<p>
black-box
<p>
<a href="https://docs.seldon.io/projects/alibi/en/stable/methods/CEM.html">CEM</a>
<p>
black-box, TF/Keras
<p>
<a href="https://docs.seldon.io/projects/alibi/en/stable/methods/CF.html">Counterfactual Instances</a>
<p>
black-box, TF/Keras
<p>
<a href="https://docs.seldon.io/projects/alibi/en/stable/methods/KernelSHAP.html">Kernel SHAP</a>
<p>
black-box
<p>
<a href="https://docs.seldon.io/projects/alibi/en/stable/methods/CFProto.html">Prototype Counterfactuals</a>
<p>
black-box, TF/Keras
<p>
Classification
<p>
Categorical data
<p>
Tabular
<p>
Text
<p>
Images
<p>
Model confidentiality
<p>
<a href="https://docs.seldon.io/projects/alibi/en/stable/methods/TrustScores.html">Trust Scores</a>
<p>
black-box
<p>
<a href="https://docs.seldon.io/projects/alibi/en/stable/examples/linearity_measure_iris.html">Linearity Measure</a>
<p>
black-box
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>March 2020, currently active project
   </td>
  </tr>
  <tr>
   <td><a href="https://rasahq.github.io/whatlies/">https://rasahq.github.io/whatlies/</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://docs.responsibly.ai/word-embedding-bias.html">https://docs.responsibly.ai/word-embedding-bias.html</a>
   </td>
   <td>
<ul>

<li>Installable package

<li>Some documentation available

<li>Good to get started but possibly restricting for doing more than the things it has on the demo
</li>
</ul>
   </td>
   <td>
<ul>

<li>It seems to be not flexible enough
</li>
</ul>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://colab.research.google.com/github/pair-code/what-if-tool/blob/master/WIT_Toxicity_Text_Model_Comparison.ipynb">https://colab.research.google.com/github/pair-code/what-if-tool/blob/master/WIT_Toxicity_Text_Model_Comparison.ipynb</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>
