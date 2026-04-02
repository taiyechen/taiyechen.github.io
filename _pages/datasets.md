---
layout: archive
title: "Datasets"
permalink: /datasets/
author_profile: true
---

This section is reserved for future public dataset releases.

I am actively building and refining research datasets, but they are not yet ready for public distribution.

{% include base_path %}

{% assign ordered_datasets = site.datasets | sort:"order_number" %}

{% if ordered_datasets.size > 0 %}
  {% for post in ordered_datasets %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>No public datasets are available yet.</p>
{% endif %}
