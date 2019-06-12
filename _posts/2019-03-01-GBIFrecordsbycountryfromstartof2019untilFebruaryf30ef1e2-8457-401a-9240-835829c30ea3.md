---
layout: post
weight: 4
title: GBIF records by country from start of 2019 until February
categories: 2019-3-1
---
<table>
	<tr>
		<th>Count</th>
		<th>Country</th>
	</tr>
{% for item in site.data.GBIFrecordsbycountryfromstartof2019untilFebruary %}
	<tr>
		<td>{{ item.Count }}</td>
		<td>{{ item.Country }}</td>
	</tr>
                     {% endfor %}
</table>
