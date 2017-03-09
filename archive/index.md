---
title: Archive
layout: posts

---

Blog posts up till now:

<ul>
{% for post in site.posts %}
    <li><a href='{{ post.url }}'>
    {% if post.title %}
        {{ post.title }}
    {% else %}
        {{ "No title" }}
    {% endif %}
    </a></li>
{% endfor %}
</ul>