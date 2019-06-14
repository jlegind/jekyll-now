---
layout: post
weight: 4
title: GBIF records by country from start of 2019 until May
categories: 2019-6-1
---
<table>
	<tr>
		<th>Count</th>
		<th>Country</th>
	</tr>
{% for item in site.data.GBIFrecordsbycountryfromstartof2019untilMay %}
	<tr>
		<td>{{ item.Count }}</td>
		<td>{{ item.Country }}</td>
	</tr>
                     {% endfor %}
</table>
