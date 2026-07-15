---
layout: page
title: Blog
description: Practical tech help for small business owners — AI tools, security basics, and the software decisions that actually matter.
permalink: /blog/
---

<div class="row">
  {% if site.posts.size > 0 %}
    {% for post in site.posts %}
      {% include article.html %}
    {% endfor %}
  {% else %}
    <p>No posts yet — check back soon.</p>
  {% endif %}
</div>
