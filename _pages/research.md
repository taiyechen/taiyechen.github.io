---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research spans international economics and an emerging line of work in AI governance. In AI-related work, I focus on AI governance, export control policies, and AI's economic impact. In economics, I focus on exchange rates, trade invoicing, global value chains, and geoeconomic fragmentation.

{% include base_path %}

{% assign economics_projects = site.research | where: "research_area", "economics" | sort: "order_number" %}
{% assign ai_governance_projects = site.research | where: "research_area", "ai-governance" | sort: "order_number" %}

<h2 class="archive__subtitle">AI Governance</h2>

<p class="research-section-note">
  Papers:<br>
  <span>* indicates a paper's first author(s).</span>
</p>

{% if ai_governance_projects.size > 0 %}
  {% for post in ai_governance_projects %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>AI governance research entries will appear here as they are added.</p>
{% endif %}

<h2 class="archive__subtitle">Economics</h2>

{% if economics_projects.size > 0 %}
  {% for post in economics_projects %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>Economics research entries will appear here as they are added.</p>
{% endif %}
