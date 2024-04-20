# Trying a new page

## Get to know me

<a href="{{ site.about }}">About me</a>

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
