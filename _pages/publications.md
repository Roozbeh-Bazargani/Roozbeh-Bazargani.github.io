---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<div style="margin-top:0.75em;"></div>

Research Highlights
=====

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
