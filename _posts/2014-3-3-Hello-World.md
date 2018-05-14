---
layout: post
title: Reading data!
categories: 2014-3-3
---

## This should be band data

{% for item in site.data.band %}
  {{ item.theme }} - {{ item.likes }}
{% endfor %}
