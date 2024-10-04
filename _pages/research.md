---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

My academic research focuses on how exchange rate fluctuations influence trade and global value chain (GVC) participation.

One strand of this research investigates how dominant currency invoicing, particularly in US dollars, shapes countries' integration into GVCs. Another strand examines the impact of exchange rate volatility on resource allocation and its broader implications for economic competitiveness.

My second major research agenda explores the effects of geoeconomic fragmentation and debt sustainability. I analyze how geopolitical tensions impact economic gains and losses for countries in different groups, as well as how these dynamics influence their integration into the global financial system and expose vulnerabilities in their debt structures.

Across these projects, I employ econometric analysis, advanced quantitative methods, and real-world data to address critical macroeconomic challenges in global trade and development.


### Current research projects include:

**Job Market Paper: "The Impact of Trade Invoicing Decisions on Global Value Chain Participation: An Empirical Analysis"**

 Over the past three decades, globalization has led to a highly interconnected global production network. This paper examines the impact of exchange rate fluctuations on forward and backward participation in global value chains (GVCs) through the lens of exchange rate passthrough and dominant currency invoicing. Specifically, it investigates how dominant currency invoicing by non-dominant countries alters the effects of exchange rate movements on general, backward, and forward GVC participation. Utilizing a sample of 96 countries from 1990 to 2020, the findings confirm that trade invoiced in dominant currencies is more sensitive to movements of those currencies. A stronger dominant currency tends to dampen overall trade, with a particularly significant impact on GVC backward linkages, which subsequently affects forward participation patterns in the long run.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
