---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

This section highlights my more developed economics research, including working papers and job market paper materials.

My current work focuses on international economics, development, and macroeconomics, with particular interest in exchange rates, trade invoicing, global value chains, geoeconomic fragmentation, and debt sustainability.

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% if ordered_pages.size > 0 %}
  {% for post in ordered_pages %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>Research entries will appear here as they are added.</p>
{% endif %}
