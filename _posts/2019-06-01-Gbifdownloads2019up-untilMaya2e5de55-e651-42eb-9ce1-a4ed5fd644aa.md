---
layout: post
weight: 2
title: Gbif downloads 2019 up-until May
categories: 2019-6-1
---
<table>
	<tr>
		<th>ISO</th>
		<th>Records</th>
		<th>Downloads</th>
		<th>Users</th>
	</tr>
{% for item in site.data.Gbifdownloads2019up-untilMay %}
	<tr>
		<td>{{ item.ISO }}</td>
		<td>{{ item.Records }}</td>
		<td>{{ item.Downloads }}</td>
		<td>{{ item.Users }}</td>
	</tr>
                     {% endfor %}
</table>
