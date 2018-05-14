---
layout: post
title: Reading data!
---

## This should be band data

{% for item in site.data.band %}
  {{ item.theme }} - {{ item.likes }}
{% endfor %}
