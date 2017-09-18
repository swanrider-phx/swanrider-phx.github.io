---
title: Blog
permalink: "/blog/"
layout: blog
---

{% assign post = site.posts.first %}
{% assign content = post.content %}

{{content}}