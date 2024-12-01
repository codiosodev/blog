---
title: "Showing posts"
tags:
    - user manual
    - writing format
date: "2024-12-01"
thumbnail: "/assets/img/thumbnail/sample.png"
bookmark: true
---

This section deals with the step-by-step process of how to write and publish posts on your site.

{% for post in site.posts %} 
    {{ post.date | date: "%b %-d, %Y" }}
    {{ post.title }}
{% endfor %} 