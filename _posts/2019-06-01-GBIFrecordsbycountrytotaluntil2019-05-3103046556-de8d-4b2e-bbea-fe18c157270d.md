---
layout: post
weight: 3
title: GBIF records by country total until 2019-05-31
categories: 2019-6-1
---
<table>
	<tr>
		<th>Count</th>
		<th>Country</th>
	</tr>
{% for item in site.data.GBIFrecordsbycountrytotaluntil2019-05-31 %}
	<tr>
		<td>{{ item.Count }}</td>
		<td>{{ item.Country }}</td>
	</tr>
                     {% endfor %}
</table>
