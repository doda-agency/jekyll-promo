---
layout: page
title: Blog
permalink: /blog/
---

# Hostinger Blog

Welcome to our blog, where we share insights, tips, and information about web hosting, website building, and getting the most out of Hostinger's services.

<div class="blog-list">
  {% for post in site.posts %}
    <article class="blog-card">
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      
      <div class="blog-meta">
        <span class="blog-date">{{ post.date | date: "%B %d, %Y" }}</span>
        
        {% if post.categories %}
        <div class="blog-categories">
          {% for category in post.categories %}
            <span class="blog-category">{{ category }}</span>
          {% endfor %}
        </div>
        {% endif %}
      </div>
      
      <div class="blog-excerpt">
        {{ post.content | strip_html | truncatewords: 50 }}
      </div>
      
      <a href="{{ post.url | relative_url }}" class="blog-read-more">Read More →</a>
    </article>
  {% endfor %}
</div>

## Ready to Get Started with Hostinger?

Whether you're looking to create a new website, improve your hosting experience, or explore our Horizon AI website builder, Hostinger has the perfect solution for you.

{% include cta.html %}