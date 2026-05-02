---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<div class="research-page">

<p class="research-intro">My research spans international economics and an emerging line of work in AI governance. Across these projects, I study how policy choices shape cross-border markets, development, and technological risk. My economics work uses empirical tools to examine exchange rates, trade invoicing, and global value chains; my AI governance work focuses on incident monitoring, export control policies, and AI's economic impact.</p>

{% include base_path %}

{% assign economics_projects = site.research | where: "research_area", "economics" | sort: "order_number" %}
{% assign ai_governance_projects = site.research | where: "research_area", "ai-governance" | sort: "order_number" %}

<h2 class="research-section-title">AI Governance</h2>

<p class="research-section-summary">I approach AI governance as a problem of measurement, institutional design, and political economy: how to make AI risks observable, how to build oversight capacity, and how to evaluate the economic consequences of AI deployment.</p>

<p class="research-section-note">
  <span><span class="author-marker">*</span> indicates equal first authorship.</span>
</p>

{% if ai_governance_projects.size > 0 %}
  {% for post in ai_governance_projects %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>AI governance research entries will appear here as they are added.</p>
{% endif %}

<h2 class="research-section-title">International Economics</h2>

<p class="research-section-summary">My international economics work studies how exchange rates, currency invoicing, and trade integration shape global value chain participation and structural change, especially for economies navigating geoeconomic fragmentation.</p>

{% if economics_projects.size > 0 %}
  {% for post in economics_projects %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>Economics research entries will appear here as they are added.</p>
{% endif %}

</div>
