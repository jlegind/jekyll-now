---
layout: post
title: GBIF records by country from_start-of-year
categories: 2018-6-1
---
<table>
	<tr>
		<th>Count</th>
		<th>Country</th>
	</tr>
{% for item in site.data.hive_count_in-year2018-06-01 %}
	<tr>
		<td>{{ item.Count }}</td>
		<td>{{ item.Country }}</td>
	</tr>
                     {% endfor %}
</table>