---
layout: post
weight: 2
title: Gbif downloads 2018 up-until August
categories: 2018-8-1
---
<table>
	<tr>
		<th>ISO</th>
		<th>Records</th>
		<th>Downloads</th>
		<th>Users</th>
	</tr>
{% for item in site.data.Gbifdownloads2018up-untilAugust %}
	<tr>
		<td>{{ item.ISO }}</td>
		<td>{{ item.Records }}</td>
		<td>{{ item.Downloads }}</td>
		<td>{{ item.Users }}</td>
	</tr>
                     {% endfor %}
</table>