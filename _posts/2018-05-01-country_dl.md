---
layout: post
title: GBIF stats May
categories: 2018-01-01
---
<table><tr><th>ISO</th><th>Records</th><th>Downloads</th><th>Users</th></tr>
{%for item in site.data.downloads_country.csv%}
        <tr>
            <td>{{ item.theme }}</td>
            <td>{{ item.likes }}</td>
        </tr>
            {% endfor %}
</table>