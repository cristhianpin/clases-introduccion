---
layout: "home"
limit: 10
show_excerpts: true
entries_layout: list
---

{% for post in site.post %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

