---
layout: post
title: GBIF stats June
categories: 2018-6-1
---

<table>
	<tr>
		<th>ISO</th>
		<th>Records</th>
		<th>Downloads</th>
		<th>Users</th>
	</tr>
{% for item in site.data.downloads_country2018-06-01 %}
        <tr>
            <td>{{ item.ISO }}</td>
            <td>{{ item.Records }}</td>
            <td>{{ item.Downloads }}</td>
            <td>{{ item.Users }}</td>
        </tr>
            {% endfor %}
</table>
