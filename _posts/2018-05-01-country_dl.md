---
layout: post
weight: 2
title: GBIF download stats for May
categories: 2018-5-1
---

<table>
		<tr>
				<th>ISO</th>
				<th>Records</th>
				<th>Downloads</th>
				<th>Users</th>
		</tr>

				{% for item in site.data.downloads_country %}

		<tr>
				<td>{{ item.ISO }}</td>
				<td>{{ item.Records }}</td>
				<td>{{ item.Downloads }}</td>
				<td>{{ item.Users }}</td>
		</tr>
				{% endfor %}
</table>
