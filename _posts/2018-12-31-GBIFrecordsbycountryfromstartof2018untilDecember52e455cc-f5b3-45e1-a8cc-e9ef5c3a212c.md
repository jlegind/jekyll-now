---
layout: post
weight: 4
title: GBIF records by country from start of 2018 until December
categories: 2018-12-31
---
<table>
	<tr>
		<th>Count</th>
		<th>Country</th>
	</tr>
{% for item in site.data.GBIFrecordsbycountryfromstartof2018untilDecember %}
	<tr>
		<td>{{ item.Count }}</td>
		<td>{{ item.Country }}</td>
	</tr>
                     {% endfor %}
</table>