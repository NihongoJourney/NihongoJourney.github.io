---
title: "Overview"
permalink: /philosophy/
published: true
layout: posts
---

The following posts discuss the guiding principles behind the Nihongo Journey framework. Think of these as the mindset underlying the site.

<ul>
{% for philosophy in site.philosophies %}
  <li>
    <h3 class="post-title"><a href="{{ philosophy.link }}">{{ philosophy.title }}</a></h3>
  </li>
{% endfor %}
<ul>
