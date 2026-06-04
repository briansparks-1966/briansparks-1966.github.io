---
layout: default
title: Home
---

# Tallgrass Code

Practical NEC code articles, Electrical Trade Education, Construction, Utility

## Recent Articles

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}

## Topics

- NEC Code Articles
- Grounding and Bonding
- NEC Calculations
- Theory
- Tools of the Trade
- Documents
- Continuing Education

  ## Site Pages

- [About](about.html)
- Troubleshooting
- Watthour Metering
- Transformers
- Consulting
