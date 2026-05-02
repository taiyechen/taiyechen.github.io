---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research spans international economics and an emerging line of work in AI governance. In economics, I focus on exchange rates, trade invoicing, global value chains, and geoeconomic fragmentation. In AI governance, I am developing work on incident monitoring, public-interest oversight, and institutional approaches to AI risk governance.

{% include base_path %}

{% assign economics_projects = site.research | where: "research_area", "economics" | sort: "order_number" %}
{% assign ai_governance_projects = site.research | where: "research_area", "ai-governance" | sort: "order_number" %}

## Economics

{% if economics_projects.size > 0 %}
  {% for post in economics_projects %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>Economics research entries will appear here as they are added.</p>
{% endif %}

## AI Governance

This line of work focuses on AI incident monitoring, governance capacity, and practical approaches to public-interest oversight.

{% if ai_governance_projects.size > 0 %}
  {% for post in ai_governance_projects %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>AI governance research entries will appear here as they are added.</p>
{% endif %}
