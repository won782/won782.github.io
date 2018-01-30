---
layout: single
title: "Extracurriculars"
permalink: "/extracurriculars/"
---

<ul>
  {% for item in site.extracurriculars %}
    <p>
      <h3><a href="{{ item.url }}">{{ item.title }}</a></h3>
      - {{ item.headline }}</br>
      <small style="text-align:right">{{ item.date | date: '%B %d, %Y' }}</small>
    </p>
  {% endfor %}
</ul>