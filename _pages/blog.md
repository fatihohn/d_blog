---
layout: section
title: blog
permalink: blog
pagination: 
  enabled: true
  category: blog
  permalink: /:num/
  per_page: 5
---
{% include sections/last_post.html last_post=site.blog.last %}
{% include sections/items_except_last.html items=site.blog%}
