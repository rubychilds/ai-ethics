# Summary

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
   <td>Scikit-fairness, part of scikit-lego
   </td>
   <td>Regression and Binary Classification
   </td>
   <td>
<ul>

<li>Regression fairness (no formal name)

<li>Demographic Parity

<li>Equal Opportunity Difference
</li>
</ul>
   </td>
   <td>
<ul>

<li>Pre-processing: information filter

<li>Model building: constraints for logistic regression only

<li>Post-modelling correction: meta-estimators
</li>
</ul>
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td>IBM Fairness 360
   </td>
   <td>Binary Classification
   </td>
   <td>
<ul>

<li>Statistical Parity Difference

<li>Equal Opportunity Difference

<li>Average Odds Difference

<li>Disparate Impact

<li>Theil Index
</li>
</ul>
   </td>
   <td>Dataset Reweighing
<p>
Optimised Preprocessing
<p>
Adversarial Debiasing
<p>
Reject Option Based Classification
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td>Aequitas tool
   </td>
   <td>Binary Classification
   </td>
   <td>
<ul>

<li>(True / False) Positive / Negative Rates

<li>Discovery Rates

<li>Omission Rates
</li>
</ul>
   </td>
   <td>N/A
<p>
Fairness Auditing tool
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td>Google What-if tool
   </td>
   <td>Both (multi-class and regression)
   </td>
   <td>Group fairness (definitions<a href="https://pair-code.github.io/what-if-tool/ai-fairness.html"> here</a>):
<ul>

<li>Group unaware

<li>Demographic parity

<li>Equal opportunity

<li>Equal accuracy

<li>Group thresholds

<p>
Individual fairness:
<ul>

<li>Counterfactual fairness
</li>
</ul>
</li>
</ul>
   </td>
   <td>N/A - exploratory (e.g. decision boundary threshold manipulation)
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td>Fairlearn
   </td>
   <td>Binary Classification <em>(Regression is mentioned, but no example)</em>
   </td>
   <td>demographic parity difference, demographic parity ratio, difference from summary, equal odds, equal odds ratio, false negative rate, false positive rate, group max, group min, group summary
   </td>
   <td>Exponentiated Gradient, GridSearch, Threshold Optimizer
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td>PyMetrics
   </td>
   <td>Classification,
<p>
<em>(Regression is mentioned, but no example)</em>
   </td>
   <td>
<ul>

<li>
Disparate impact
</li>
</ul>
   </td>
   <td>N/A
   </td>
   <td><em>It says yes, but no example available</em>
   </td>
  </tr>
</table>
