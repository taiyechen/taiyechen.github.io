---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This section collects formal publications, especially co-authored policy briefs, issue papers, and related professional outputs.

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
