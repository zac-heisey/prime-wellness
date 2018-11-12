---
title: Blog
permalink: "/blog/"
layout: page
description: Useful resources related to physical therapy, yoga, cryotherapy,<br>
  nutrition, fitness, and general health and wellness.
seo-title: Health & Wellness Blog
seo-description: Guides, articles, and other resources related to physical therapy,
  yoga, cryotherapy, fitness, nutrition, and more. Check out the RISE Prime Wellness
  blog.
featured-image: uploads/prime-blog.jpg
---

# Recent Posts

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h2>
        <a class="post-link" href="{{ post.url }}">{{ post.title }}</a>
      </h2>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" }}">via RSS</a></p>
