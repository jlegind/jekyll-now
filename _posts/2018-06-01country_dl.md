---
layout: post
title: GBIF stats June
categories: 2018-06-01
---
<table><tr><th>ISO</th><th>Records</th><th>Downloads</th><th>Users</th></tr>
{%for item in site.data.downloads_country2018-06-01.csv%}
        <tr>
            <td>{{ item.theme }}</td>
            <td>{{ item.likes }}</td>
        </tr>
            {% endfor %}
</table>