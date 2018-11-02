---
layout: post
weight: 2
title: Gbif downloads 2018 up-until November
categories: 2018-11-01
---
<table>
	<tr>
		<th>ISO</th>
		<th>Records</th>
		<th>Downloads</th>
		<th>Users</th>
	</tr>
{% for item in site.data.Gbifdownloads2018up-untilNovember %}
	<tr>
		<td>{{ item.ISO }}</td>
		<td>{{ item.Records }}</td>
		<td>{{ item.Downloads }}</td>
		<td>{{ item.Users }}</td>
	</tr>
                     {% endfor %}
</table>