---
layout: project_page
title: IBM professional certificate project
description: 
img: assets/img/IBM_cover_img.jpg
importance: 2
category: fun
related_publications: true
---
Classification model built using XGBoost. Tools used: API, data wrangling, EDA, feature engineering, density plots, predictive model, feature importance, confusion matrix, model evaluation (cross validation), hyperparameter tuning, cost estimation. 

This project was conducted as an applied datascience capstone project for the Profesional Data science certificate by IBM.

The goal of this project was to predict whether SpaceX’s Falcon 9 first stage will land successfully after launch.
A successful landing significantly reduces launch costs since the rocket can be reused. Understanding what affects successful landings helps estimate costs and guide competitive bidding by other launch providers.

<h3>Summary Slides</h3>
<iframe 
  src="{{ 'assets/slides/capstone_project_short_version.pdf' | relative_url }}" 
  width="75%" 
  height="600px">
</iframe>

<h3>Jupyter notebook</h3>
{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/capstone_project.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
  {% jupyter_notebook jupyter_path %}
{% else %}
   <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}

<!-- 
  {% assign jupyter_path = "assets/jupyter/jupyter-labs-eda-dataviz-v2.ipynb" | relative_url %}
  {% capture notebook_exists %}{% file_exists assets/jupyter/jupyter-labs-eda-dataviz-v2.ipynb %}{% endcapture %}
  {% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
  {% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
  {% endif %}
  
{% endif %}
{:/nomarkdown}
-->

