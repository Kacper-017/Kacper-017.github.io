---
layout: home
title: Your Name - Web Developer
---

# Welcome to My Portfolio!

I'm a passionate web developer showcasing my work here. Check out my projects below:

{% for post in site.posts %}
  ## [{{ post.title }}]({{ post.url }})
  {{ post.excerpt }}
{% endfor %}
