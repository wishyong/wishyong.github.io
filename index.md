---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}


### About Me

My name is wish. Talk is cheap ,show me the code is my motto. Come on :).

### What i want to do 

Just want to record what I'm doing and thinking in my life.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

