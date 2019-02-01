---
layout: post
weight: 1
title: Total Download Stats 2018-12-31
categories: 2018_end_year
---
<table>
	<tr>
		<th>Type</th>
		<th>Count</th>
	</tr>
{% for item in site.data.TotalDownloadStats2018-12-31 %}
	<tr>
		<td>{{ item.Type }}</td>
		<td>{{ item.Count }}</td>
	</tr>
                     {% endfor %}
</table>
