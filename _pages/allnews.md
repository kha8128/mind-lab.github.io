---
title: "News | Mind Lab | Department of Mechanical Engineering at Binghamton University"
layout: textlay
excerpt: "News | Mind Lab | Department of Mechanical Engineering at Binghamton University"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}

<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
