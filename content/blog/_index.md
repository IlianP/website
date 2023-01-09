---
title: Data science blog
description: |
  My articles are typically about new libraries and services that I try out. Occasionally I discuss data science philosophy or project management.
author: "Paul Simmering"
show_post_thumbnail: true
thumbnail_left: true # for list-sidebar only
show_author_byline: false
show_post_date: true
show_button_links: false
# for listing page layout
layout: list-sidebar # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: Data science blog
  description: |
    My articles are typically about new libraries and services that I try out. Occasionally I discuss data science philosophy or project management. Illustration by <a href="https://unsplash.com/@sonance">Viktor Forgacs</a> on <a href="https://unsplash.com/photos/7C5N8yLaeDI">Unsplash</a>
    
  author: ""
  text_link_label: Subscribe via RSS
  text_link_url: /index.xml
  show_sidebar_adunit: false # show ad container

# set up common front matter for all pages inside blog/
cascade:
  author: "Paul Simmering"
  show_author_byline: false
  show_post_date: true
  show_comments: true # see site config to choose Disqus or Utterances
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent posts
    text_link_url: /blog/
    show_sidebar_adunit: false # show ad container
---

** No content below YAML for the blog _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside blog/. You may still override any of these by changing them in a page's front matter.**