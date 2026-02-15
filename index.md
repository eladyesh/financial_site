---
title: Home
---

# Investment Research

Long-form notes, theses, and market analysis.

## Latest posts
<ul>
{% raw %}{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small>— {{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
{% endfor %}{% endraw %}
</ul>

