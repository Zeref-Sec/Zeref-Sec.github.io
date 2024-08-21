---
layout: default
---

# Welcome to My Hacker Blog

This is a blog about technology, hacking, and cybersecurity.

## Recent Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## About Me

I'm a passionate developer and security enthusiast. This blog is where I share my thoughts, discoveries, and projects related to the world of technology and cybersecurity.

[Read more about me](./about.html)
