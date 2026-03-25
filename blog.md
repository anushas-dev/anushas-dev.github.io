---
---
layout: page
title: Blog
permalink: /blog/
pagination:
  enabled: true
  per_page: 5
  permalink: '/blog/:num/'
---

# Blog

{% if paginator.posts == empty %}
No posts yet. Check back soon!
{% else %}
{% for post in paginator.posts %}
<article>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p><small>{{ post.date | date: "%B %-d, %Y" }}</small></p>
  {{ post.excerpt }}
  <p><a href="{{ post.url }}">Read more →</a></p>
</article>
<hr/>
{% endfor %}

<nav class="pagination" role="navigation">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}">&laquo; Newer</a>
  {% endif %}
  <span>Page {{ paginator.page }} of {{ paginator.total_pages }}</span>
  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}">Older &raquo;</a>
  {% endif %}
</nav>
{% endif %}
