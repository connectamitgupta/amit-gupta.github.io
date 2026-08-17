---
layout: default
title: Case Studies
---

# Case Studies

A few projects worth a closer look — what the problem was, what I did, and what changed.

<div class="cards">
  {% for cs in site.case_studies %}
  <a class="card card-link" href="{{ cs.url | relative_url }}">
    <h3>{{ cs.title }}</h3>
    <p class="meta">{{ cs.company }} · {{ cs.timeframe }}</p>
    <p>{{ cs.summary }}</p>
  </a>
  {% endfor %}
</div>
