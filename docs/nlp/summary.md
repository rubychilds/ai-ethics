## Summary

<table>
  <tr>
   <td>Tool
   </td>
   <td>Regression / Classification (binary vs. multi-class)
   </td>
   <td>Fairness metrics covered
   </td>
   <td>Mitigation covered
   </td>
   <td>Handles multi-class protected feature?
   </td>
  </tr>
  <tr>
   <td>Debiaswe <a href="https://github.com/tolga-b/debiaswe">https://github.com/tolga-b/debiaswe</a>
   </td>
   <td>Embeddings instead of downstream task
   </td>
   <td>No
   </td>
   <td>Yes
   </td>
   <td>No(genderonly in the form of binary, pairs)
   </td>
  </tr>
  <tr>
   <td>Sent debias <a href="https://github.com/pliang279/sent_debias">https://github.com/pliang279/sent_debias</a>
   </td>
   <td>Again embedding instead of downstream task
   </td>
   <td>No
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td>AllenNLP Interpret
<p>
<a href="https://allennlp.org/interpret">https://allennlp.org/interpret</a>
   </td>
   <td>Binary / Multi-class Classification (all levels of NLP tasks)
   </td>
   <td>No
   </td>
   <td>No
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/TimeTraveller-San/RAN-Debias">https://github.com/TimeTraveller-San/RAN-Debias</a>
   </td>
   <td>N/A Embedding focused
   </td>
   <td>No
   </td>
   <td>Yes (Genderonly included with package. Possibility for users to add others & retrain)
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/TManzini/DebiasMulticlassWordEmbedding">https://github.com/TManzini/DebiasMulticlassWordEmbedding</a>
   </td>
   <td>N/A Embedding focused
   </td>
   <td>No
   </td>
   <td>Yes - retrains word embedding wrt 
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td><a href="https://docs.seldon.io/projects/alibi/en/stable/overview/algorithms.html">https://docs.seldon.io/projects/alibi/en/stable/overview/algorithms.html</a>
   </td>
   <td>Classification/Regression
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td><a href="https://rasahq.github.io/whatlies/">https://rasahq.github.io/whatlies/</a>
   </td>
   <td>Did not review
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
   <td>This tool allows you to calculate WEAT scores to detect embedding bias
   </td>
   <td>Yes, only WEAT
   </td>
   <td>Yes but not recommended as method might be out of date
   </td>
   <td>Probably not
   </td>
  </tr>
  <tr>
   <td><a href="https://colab.research.google.com/github/pair-code/what-if-tool/blob/master/WIT_Toxicity_Text_Model_Comparison.ipynb">https://colab.research.google.com/github/pair-code/what-if-tool/blob/master/WIT_Toxicity_Text_Model_Comparison.ipynb</a>
   </td>
   <td>Did not review
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>
