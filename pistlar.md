---
layout: default
title: Pistlar
---
# Nýustu fréttir

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>