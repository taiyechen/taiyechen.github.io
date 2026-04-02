---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My current work focuses on international economics, development, and macroeconomics, with particular interest in exchange rates, trade invoicing, global value chains, and geoeconomic fragmentation.

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% if ordered_pages.size > 0 %}
  {% for post in ordered_pages %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>Research entries will appear here as they are added.</p>
{% endif %}
