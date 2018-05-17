---
layout: post
title: Reading data!
categories: 2014-3-3
---

### This should be band data

<table>
	<tr>
		<th>THEME</th>
		<th>YEAR</th>
	</tr>

		{% for item in site.data.band %}
	<tr>
		<td>{{ item.theme }}</td>
		<td>{{ item.likes }}</td>
	</tr>
		{% endfor %}
</table>
