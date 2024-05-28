---
layout: archive
title: "Publication"
permalink: /publication/
author_profile: true
redirect_from: 
  - "/publication/"
  - "/publication.html"
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publication reversed %}
  {% include archive-single.html %}
{% endfor %}
