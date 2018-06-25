---
layout: post
title: Total download stats
categories: 2018-6-1
---
<table>
	<tr>
		<th>Type</th>
		<th>Count</th>
	</tr>
{% for item in site.data.downloads_total2018-06-01 %}
	<tr>
		<td>{{ item.Type }}</td>
		<td>{{ item.Count }}</td>
	</tr>
                     {% endfor %}
</table>