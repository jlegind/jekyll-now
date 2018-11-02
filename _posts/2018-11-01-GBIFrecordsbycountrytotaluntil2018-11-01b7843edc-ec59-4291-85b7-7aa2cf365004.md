---
layout: post
weight: 3
title: GBIF records by country total until 2018-11-01
categories: 2018-11-01
---
<table>
	<tr>
		<th>Count</th>
		<th>Country</th>
	</tr>
{% for item in site.data.GBIFrecordsbycountrytotaluntil2018-11-01 %}
	<tr>
		<td>{{ item.Count }}</td>
		<td>{{ item.Country }}</td>
	</tr>
                     {% endfor %}
</table>