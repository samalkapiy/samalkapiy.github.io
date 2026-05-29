---
layout: project_page
title: Credit card fraud detection with XGBoost
description: "model built to predict fraudulent transactions and estimate the monthly net savings. (XGBoost, ROC-AUC score, cross validation)"
img: assets/img/credit_card_project_img.png
importance: 1
category: fun
related_publications: true
---
Classification model built using XGBoost (Tools: pandas, XGBoost,feature importance, ROC-AUC score, cross validation, learning curves, saving estimation, density plots)

The goal of this project was to build a model that can predict whether a credit card transaction is fraudulent or not. Using the predictive model, this project also estimates the total net savings by identifying the fraudulent transactions. The input dataset contains 10,000 credit card transactions with 98.49% being non-fraudulent and 1.51% being fraudulent transactions. 
Predictive model building and exploratory data analysis is summarized in the slides below. The full notebook used is also added below. 


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
