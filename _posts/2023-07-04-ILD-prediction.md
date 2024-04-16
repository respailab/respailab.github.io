---
layout: post
title: ILD Classification and Infection Prediction
date: 2024-04-15 08:57:00-0400
description: Predicting weather a person will be infected or not by consuming prescribed medicines for ILD.
tags: jupyter ILD
categories: health disease
giscus_comments: false
related_posts: false
---

This notebook will guide you to predict weather a person is infected or not based on CT scan images.

{% raw %}

{% endraw %}

{::nomarkdown}
{% assign jupyter_path = 'assets/jupyter/ILD_Infection_Detection.ipynb' | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/ILD_Infection_Detection.ipynb %}{% endcapture %}
{% if notebook_exists == 'true' %}
  {% jupyter_notebook jupyter_path %}
{% else %}
  <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}