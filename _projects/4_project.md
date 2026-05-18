---
layout: project_page
title: Credit card fraud detection with XGBoost
description: 
img: assets/img/credit_card_project_img.png
importance: 3
category: fun
related_publications: true
---
The goal of this project was to build a model that can predict whether a credit card transaction is fraudulent or not. The input dataset contains 10,000 credit card transactions. 
The goal of this project was to predict whether SpaceX’s Falcon 9 first stage will land successfully after launch.
A successful landing significantly reduces launch costs since the rocket can be reused. Understanding what affects successful landings helps estimate costs and guide competitive bidding by other launch providers.

<h3>Summary Slides</h3>
<iframe 
  src="{{ 'assets/slides/fraud_detection.pdf' | relative_url }}" 
  width="75%" 
  height="600px">
</iframe>

<h2>Jupyter notebook</h2>
{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/Credit_card_fraud_detection.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
  {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
