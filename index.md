---
title: "Home Page"
---

Roughly every week, I watch a movie and do my best to critique it.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>