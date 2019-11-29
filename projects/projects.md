---
layout: default
---

# Projects
<ul>
  {% for projects in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
