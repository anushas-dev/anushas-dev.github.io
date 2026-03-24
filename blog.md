---
layout: page
title: Blog
permalink: /blog/
---

# Blog

Recent posts are listed below. Click a title to read the full post.

{% if site.posts.size == 0 %}
No posts yet. Check back soon!
{% else %}
{% for post in site.posts limit: 10 %}
<article>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p><small>{{ post.date | date: "%B %-d, %Y" }}</small></p>
  {{ post.excerpt }}
  <p><a href="{{ post.url }}">Read more →</a></p>
</article>
<hr/>
{% endfor %}
{% endif %}
