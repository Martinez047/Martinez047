---
layout: default
title: Home
---

# Welcome to My Python and Linux World!

I'm a passionate Python programmer and Linux enthusiast. This is my corner of the internet where I share my experiences, tips, and projects related to Python programming and Linux.

## Latest Articles

<!-- Replace with your latest articles or blog posts -->
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Let's Connect

I'm always excited to connect with fellow Python programmers and Linux enthusiasts. Feel free to reach out to me via [email](chikadayamartin@outlook.com) 

Happy coding and exploring the world of Python and Linux!
