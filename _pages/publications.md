---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

# Task Me Anything

**Authors**: Jieyu Zhang, Weikai Huang, Zixian Ma, Oscar Michel, Dong He, Tanmay Gupta, Wei-Chiu Ma, Ali Farhadi, Aniruddha Kembhavi, Ranjay Krishna

**Status**: Under Review

[Preprint](#) | [Website](#) | [Code](#)



{% if site.author.googlescholar %}
  # <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
