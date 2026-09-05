---
title: "News"
layout: textlay
excerpt: "AfricaNLP Lab at Bayero University Kano."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
