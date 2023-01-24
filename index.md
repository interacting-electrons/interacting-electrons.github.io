---
layout: default
---

# Interacting Electrons Homepage.
This is the website for Andy's course on interacting electrons. Content will be added as it becomes available.

## News
<ul>
  {% for post in site.posts %}
      <a href="{{ post.url }}">{{ post.title }}</a>
  {% endfor %}
</ul>
