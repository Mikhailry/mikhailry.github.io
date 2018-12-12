---
layout: archive
permalink: /posts/
title: "Project posts by tags"
author_profile: true
header:
    image: "/images/projects.jpeg"
---

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
