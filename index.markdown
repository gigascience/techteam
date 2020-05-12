---
layout: default
---
<h1>Latest Minutes</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="techteam/{{ post.url }}">{{ post.title }}: {{post.date | date_to_long_string}}</a></h2>
    </li>
  {% endfor %}
</ul>
