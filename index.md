---
layout: default
---

{% for post in site.posts %}
<h2><a href="{{post.url}}">{{post.date|date_to_long_string}} - {{post.title}}</a></h2>

<div>{{post.excerpt}}</div>

<hr />
{% endfor %}
