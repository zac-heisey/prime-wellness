---
title: Blog
permalink: "/blog/"
layout: page
description: 
seo-title: Health & Wellness Blog
seo-description: Guides, articles, and other resources related to physical therapy,
  yoga, cryotherapy, fitness, nutrition, and more. Check out the RISE Prime Wellness
  blog.
featured-image: uploads/images/pic05.jpg
---

Welcome to the RISE Prime Wellness blog. Our goal is provide useful resources related to physical therapy, yoga, cryotherapy, fitness, nutrition, fitness, and general health and wellness. Enjoy!

# Recent Posts

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.url }}">{{ post.title }}</a>
      </h2>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.url }}">via RSS</a></p>
