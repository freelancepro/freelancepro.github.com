---
layout: page
title: Allo Freelancers!
tagline: Freelancer's Reputation Platform
---
{% include JB/setup %}

Read [FreelancePro Fast Fufu](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : FreelancePro Blog
    
    author    :
      name    : FreelancePro.me
      email   : care@freelancepro.me
      github  : freelancepro
      twitter : @FreelancePro_Me

The theme should reference these variables whenever needed.
    

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


