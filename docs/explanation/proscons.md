## Pros and Cons

<table>
  <tr>
   <td><strong>Tool</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td><strong><code><a href="https://www.ibm.com/watson/explainable-ai?mhsrc=ibmsearch_a&mhq=explainable%20ai">IBM OpenScale</a></code></strong>
   </td>
   <td>
<ul>

<li>Strong emphasis on how it ensures model regulatory and business compliance, e.g. it can automatically generate a PDF fact sheet detailing metrics such as drift and bias

<li>Compatible with models and data running virtually anywhere

<li>Built for easy use by junior data scientists/analysts with simple layman assessments of models
</li>
</ul>
   </td>
   <td>
<ul>

<li>Cost - there is a lite version but the standard version costs $13,650.00 USD/Instance and $3,412.50 USD/6 Models

<li>Standard includes support to monitor up to 24 deployed models

<li>Other known limitations -<a href="https://cloud.ibm.com/docs/ai-openscale?topic=ai-openscale-rn-12ki"> https://cloud.ibm.com/docs/ai-openscale?topic=ai-openscale-rn-12ki</a>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/EthicalML/xai">EthicalML XAI</a>
   </td>
   <td>
<ul>

<li>Simple to use

<li>Aligned with the usual model development workflow
</li>
</ul>
   </td>
   <td>
<ul>

<li>Very basic
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong><a href="https://github.com/h2oai/mli-resources">MLI Resources</a></strong>
   </td>
   <td>
<ul>

<li>iPython notebook examples;

<li>5 models to use on data sets;

<li>Known and recognized leader in the space;

<li>Provides natural language explanation on how the data can be improved

<li>Python lib. indicates it can be deployed and used on Hadoop instances;

<li>h20 has a REST interface if being applied in a commercial environment

<li>Works with other Python libs for visualization
</li>
</ul>
   </td>
   <td>
<ul>

<li>Research focused examples

<li>No integration with existing ML workflows, such as SciKit Learn

<li>Examples of explainability Examples of explainability do not indicate suitability for scalability with Hadoop.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Seldon<a href="https://docs.seldon.io/projects/alibi/en/latest/"> Alibi 0.4.0</a></strong>
   </td>
   <td>
<ul>

<li>Very broad - in terms of methods, data types, etc

<li>Good list of examples - e.g. one metric in one context; useful for those unsure of what approach to apply where.

<li>Docu seems fairly complete

<li>Deals with runtime/op concerns (not just design time) 
</li>
</ul>
   </td>
   <td>
<ul>

<li>Feels very new - will be interesting to see others feedback
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong><a href="https://cloud.google.com/explainable-ai">Explainable AI</a> Google  </strong>
   </td>
   <td>
<ul>

<li>
</li>
</ul>
   </td>
   <td>
<ul>

<li>Limitation of XAI method options

<li>Have to host the model on GCP

<li>Only runs tensorflow v.1.X
</li>
</ul>
   </td>
  </tr>
</table>
