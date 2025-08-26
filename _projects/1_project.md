---
layout: project_page
title: project 1
description: with background image
img: assets/img/12.jpg
importance: 1
category: fun
related_publications: true
---

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:


<h3>Summary Slides</h3>
<article class="post-content CV clearfix">
        <embed src="assets/pdf/needs_to_update.pdf" width="75%" height="800" type="application/pdf" />

</article>

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/blog.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}


