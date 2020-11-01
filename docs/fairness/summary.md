<table>
<thead>
  <tr>
    <th rowspan="2">Tool</th>
    <th rowspan="2">Setup</th>
    <th rowspan="2">Open source user license</th>
    <th rowspan="2">Release date</th>
    <th rowspan="2">Organization</th>
    <th rowspan="2">Open for anyone to contribute code?</th>
    <th colspan="4">Models covered</th>
    <th colspan="6">Group fairness</th>
    <th colspan="2">Individual fairness</th>
    <th>Other fairness metrics</th>
    <th>Mitigation</th>
  </tr>
  <tr>
    <td>Regression</td>
    <td>Classification   (binaryoutcome)</td>
    <td>Multi-class   outcome</td>
    <td>Handles   multi-class protected feature?</td>
    <td>Demographic   parity (statistical parity)</td>
    <td>Equal   opportunity / True positive parity / false positive error rate balance</td>
    <td>Equal odds   (True positive and false positive parity)</td>
    <td>Disparate   impact</td>
    <td>Discovery   rate</td>
    <td>Omission   rate</td>
    <td>Counterfactual   fairness</td>
    <td>Sample   distortion metrics</td>
    <td></td>
    <td></td>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Scikit-fairness   / scikit-lego</td>
    <td>python (sklearn)</td>
    <td>MIT</td>
    <td>2019-03-31</td>
    <td>N/A</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>X</td>
    <td>X</td>
    <td>✓</td>
    <td>✓</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>N/A</td>
    <td>Pre-processing:   information filter</td>
  </tr>
  <tr>
    <td>IBM Fairness 360</td>
    <td>python   3.5+, R</td>
    <td>Apache 2.0</td>
    <td>2018-06-01</td>
    <td>IBM</td>
    <td>✓</td>
    <td>X</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>X</td>
    <td>✓</td>
    <td>Generalized   Entropy Index<br>     Differential Fairness and Bias Amplification <br>     (full list here:   <a href="https://aif360.readthedocs.io/en/latest/modules/generated/aif360.metrics.ClassificationMetric.html">https://aif360.readthedocs.io/en/latest/modules/generated/aif360.metrics.ClassificationMetric.html</a>)</td>
    <td>Optimized Preprocessing, Disparate Impact Remover, Equalized   Odds Post-processing, Reweighing, Reject Option Classification, Prejudice   Remover Regularizer, Calibrated Equalized Odds Postprocessing, Learning Fair   Representations, Adversarial Debiasing, Meta-Algorithm for Fair   Classification, Rich Subgroup Fairness</td>
  </tr>
  <tr>
    <td>Aequitas tool</td>
    <td>python   3.6+</td>
    <td>Custom</td>
    <td>2018-02-13</td>
    <td>UChicago</td>
    <td>✓</td>
    <td>X</td>
    <td>✓</td>
    <td>X</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>X</td>
    <td>✓</td>
    <td>✓</td>
    <td>X</td>
    <td>X</td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>Google What-if tool</td>
    <td>Tensorboard   / Jupyter or Colab notebook</td>
    <td>Apache 2.0</td>
    <td>2018-09-11</td>
    <td>Google</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>✓</td>
    <td>X</td>
    <td>Group   thresholds</td>
    <td>Threshold optimization based on fairness constraints</td>
  </tr>
  <tr>
    <td>PyMetrics audit-ai</td>
    <td>python</td>
    <td>MIT</td>
    <td>2018-05-18</td>
    <td>PyMetrics</td>
    <td>X</td>
    <td>✓</td>
    <td>✓</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>✓</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>Statistical   tests to determine chance the disparity is due to random chance (ANOVA,   4/5th, fisher, z-test, bayes factor, chi squared<br>     sim beta ratio, classifier posterior_probabilities)</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>Fairlearn</td>
    <td>python</td>
    <td>MIT</td>
    <td>2018-05-15</td>
    <td>Microsoft</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>X</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>✓</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>X</td>
    <td>Group   max / min /  summary</td>
    <td>Exponentiated Gradient, GridSearch, Threshold Optimizer</td>
  </tr>
</tbody>
</table>
