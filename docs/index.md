---
layout: default
---

{% include navbar.html %}

# Trying a new page

## Get to know me

[About me](./about.md)

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
