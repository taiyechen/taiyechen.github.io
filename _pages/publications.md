---
layout: archive
title: "Policy & Commentary"
permalink: /policy-commentary/
author_profile: true
redirect_from:
  - /publications/
---

This section collects policy briefs, issue papers, and shorter commentary pieces. More developed academic papers remain under Research.

{% include base_path %}

## Policy Briefs

{% if site.publications.size > 0 %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>No policy briefs listed yet.</p>
{% endif %}

## Blog & Commentary

{% capture written_year %}'None'{% endcapture %}
{% if site.posts.size > 0 %}
  {% for post in site.posts %}
    {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
    {% if year != written_year %}
      <h3 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h3>
      {% capture written_year %}{{ year }}{% endcapture %}
    {% endif %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>No blog or commentary pieces published yet.</p>
{% endif %}
