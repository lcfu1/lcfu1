---
layout: default
description: second的简单描述
categories: home
---

<div class="home">

  {% if site.posts.size > 0 %}
  <h2 class="post-list-heading">{{ page.list_title | default: page.title }}</h2>
    <ul class="post-list">
      {% for post in site.categories.second %}
        <li>
          {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
          <span class="post-meta">{{ post.date | date: date_format }}</span>

          <h3 style="margin-bottom: 5px;">
            <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
          </h3>
		  <span>{{ post.description }}</span>
        </li>
      {% endfor %}
    </ul>

    <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | relative_url }}">via RSS</a></p>
  {% endif %}

</div>