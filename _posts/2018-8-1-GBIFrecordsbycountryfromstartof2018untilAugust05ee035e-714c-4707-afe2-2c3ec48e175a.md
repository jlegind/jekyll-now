---
layout: post
weight: 4
title: GBIF records by country from start of 2018 until August
categories: 2018-8-1
---
<table>
	<tr>
		<th>Count</th>
		<th>Country</th>
	</tr>
{% for item in site.data.GBIFrecordsbycountryfromstartof2018untilAugust %}
	<tr>
		<td>{{ item.Count }}</td>
		<td>{{ item.Country }}</td>
	</tr>
                     {% endfor %}
</table>