---
layout: project_page
title: A/B testing. Is the ad campaign successful?
description: "A/B testing performed to statistically conclude whether the ad campaign is a success or not."
img: assets/img/A_B_testing_cover.png
importance: 4 
category: fun
related_publications: true
---
The following project analyses the business question of whether the conversion rate from the ad campaign is statistically significant or not. 

<h2>Jupyter notebook</h2>
{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/A_B_testing_ad_campaign.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
  {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
