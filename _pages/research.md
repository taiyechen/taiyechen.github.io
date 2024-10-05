---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---


My current research examines how exchange rate fluctuations affect trade and global economic integration. One key focus is how dominant currency invoicing, particularly in US dollars, influences countries' participation in global value chains (GVCs) and shapes their economic competitiveness.

My second major research agenda explores the effects of geoeconomic fragmentation and debt sustainability. I analyze how geopolitical tensions impact economic gains and losses for countries in different groups, as well as how these dynamics influence their integration into the global financial system and expose vulnerabilities in their debt structures.

Using econometric analysis and advanced quantitative methods, my work addresses critical challenges in global trade and development.


##  Current research projects include:

### Job Market Paper: "The Impact of Trade Invoicing Decisions on Global Value Chain Participation: An Empirical Analysis"

 Over the past three decades, globalization has led to a highly interconnected global production network. This paper examines the impact of exchange rate fluctuations on forward and backward participation in global value chains (GVCs) through the lens of exchange rate passthrough and dominant currency invoicing. Specifically, it investigates how dominant currency invoicing by non-dominant countries alters the effects of exchange rate movements on general, backward, and forward GVC participation. Utilizing a sample of 96 countries from 1990 to 2020, the findings confirm that trade invoiced in dominant currencies is more sensitive to movements of those currencies. A stronger dominant currency tends to dampen overall trade, with a particularly significant impact on GVC backward linkages, which subsequently affects forward participation patterns in the long run.

### Are Real Exchange Rate Undervaluation and Trade Integration Complements? An Evaluation on Employment Reallocation

  This paper explores the impact of real exchange rate (RER) undervaluation on labor reallocation to tradable sectors in the context of increasing global trade integration. Existing literature suggests that RER undervaluation effectively supports growth in developing countries by directing economic factors of production toward sectors with high learning spillovers, typically tradable sectors. Building on this premise and ac- knowledging the intensified efforts toward globalization, this study employs the Local Projection method to analyze the marginal effects of RER undervaluation on labor reallocation to tradable sectors as economies become more integrated. This approach allows for a nuanced understanding of how RER policies influence economic restruc- turing in an integrated global market, providing valuable insights for policymakers aiming to optimize trade and exchange rate strategies to foster sustainable economic growth.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
