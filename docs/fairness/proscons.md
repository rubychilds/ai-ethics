# Pros and Cons

<table>
  <tr>
   <td><strong>Tool</strong>
   </td>
   <td><strong>Key Pros</strong>
   </td>
   <td><strong>Key cons</strong>
   </td>
  </tr>
  <tr>
   <td>Scikit-fairness, part of scikit-lego
   </td>
   <td>
<ul>

<li>Easy to install

<li>Very easy to train logistic regression models to be fair.
</li>
</ul>
   </td>
   <td>
<ul>

<li>Very limited functionality

<li>Only two definitions of fairness

<li>No case studies, just simple examples on how to use
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>IBM Fairness 360
   </td>
   <td>
<ul>

<li>Great Tutorials and Demonstration Notebooks

<li>Very robust code + functionality
</li>
</ul>
   </td>
   <td>
<ul>

<li>Over-reliance on debiasing algorithms to solve problems.

<li>Quite a steep learning curve + hard to use.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Aequitas tool
   </td>
   <td>
<ul>

<li>Simple to learn and use

<li>Intuitive Web interface for non technical audience

<li>Well documented + demos
</li>
</ul>
   </td>
   <td>
<ul>

<li>Limited basic functionality to identifying bias - no mitigation

<li>Fairly surface level
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Google What-if tool
   </td>
   <td>
<ul>

<li>Easy to install (3 lines of code), runs on Jupyter Notebook, Tensorboard

<li>Easy counterfactual implementation

<li>Good for exploratory analysis if you know what you’re looking for
</li>
</ul>
   </td>
   <td>
<ul>

<li>Dependency on Google Cloud environment

<li>Does not support ensemble methods

<li>Complex UI with too much information

<li>Limited customizability

<li>Very little (no) guidance on what to look for and what it means
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Fairlearn
   </td>
   <td>
<ul>

<li>Easy to install

<li>Includes dashboard to guide the user

<li>Includes several mitigation techniques

<li>It includes equalised odds among other fairness definitions

<li>It accepts multiple values for a protected class (e.g.: Female, Male, non-binary)
</li>
</ul>
   </td>
   <td>
<ul>

<li>Regression is mentioned, but no example. This is possibly work in progress

<li>Missing documentation on mitigation techniques
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>PyMetrics
   </td>
   <td>
<ul>

<li>Easy to install

<li>Examples on how to use the library

<li>Useful for initial exploratory data analysis on fairness

<li><em>Includes adverse impact over time</em>
</li>
</ul>
   </td>
   <td>
<ul>

<li>Limited to one form of fairness definition

<li>Not enough context on fairness
</li>
</ul>
   </td>
  </tr>
</table>
