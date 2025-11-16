---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a third-year Ph.D. student in <a href="https://mmlab.ie.cuhk.edu.hk/">Multimedia Lab</a>, CUHK, supervised by Prof. <a href="https://www.ee.cuhk.edu.hk/~hsli/"> Hongsheng Li</a>. 

My research interest includes multimodal reasoning and unified understanding & generation MLLM. Please email me if you want to collaborate for academic research or have any questions.

I will be entering the job market in 2027. Please feel free to reach out if you have opportunities!


{% include_relative includes/news.md %}
{% include_relative includes/pub.md %}