---
layout: archive
title: ""
permalink: /research/
author_profile: true

---


My current research examines how exchange rate fluctuations affect trade and global economic integration. One key focus is how dominant currency invoicing, particularly in US dollars, influences countries' participation in global value chains and shapes their economic competitiveness.

My second major research agenda explores the effects of geoeconomic fragmentation and debt sustainability. I analyze how geopolitical tensions impact economic gains and losses for countries in different groups, as well as how these dynamics influence their integration into the global financial system and expose vulnerabilities in their debt structures.


##  Current research projects include:

### Job Market Paper: "The Impact of Trade Invoicing Decisions on Global Value Chain Participation: An Empirical Analysis"
[Link here](/files/JMP-TC.pdf)

 Over the past three decades, globalization has led to a highly interconnected global production network. TThis paper investigates how exchange rate fluctuations influence global value chain (GVC) participation at a disaggregated level, focusing on the role of dominant currency invoicing. Using data from 96 countries (1990–2020), the analysis shows that trade invoiced in dominant currencies is more sensitive to exchange rate movements. Dollar appreciation dampens GVC participation, particularly backward production, which in turn affects forward linkages over time. However, dominant currency invoicing mitigates some of these negative effects, highlighting its stabilizing role amid currency fluctuations. 

### "The Impact of Trade Invoicing Decisions on Global Value Chain Participation: An Empirical Analysis"

 This work examines the bidirectional relationship between dominant currency invoicing practicing in international trade and participation in Global Value Chains (GVCs). Employing local projection methods, the paper investigates two interrelated dynamics: (1) how trade invoicing in dominant currencies influences GVC participation at disaggregated levels—and (2) how integration into GVCs shapes incentives to adopt dominant currencies over domestic or partner-country currencies. Results reveal asymmetric responses: greater domiant currency usage enhances backward and forward GVC participation by reducing transaction costs and exchange rate risks, while deeper GVC integration amplifies reliance on dominant currencies to mitigate pricing mismatches and enhance contractual credibility. The findings highlight a potential self-reinforcing cycle, wherein dominant currencies and GVC linkages co-evolve, with path-dependent effects on trade structures.

### "Are Real Exchange Rate Undervaluation and Trade Integration Complements? An Evaluation on Employment Reallocation"

  This paper explores the impact of real exchange rate (RER) undervaluation on labor reallocation to tradable sectors in the context of increasing global trade integration. Existing literature suggests that RER undervaluation effectively supports growth in developing countries by directing economic factors of production toward sectors with high learning spillovers, typically tradable sectors. Building on this premise and acknowledging the intensified efforts toward globalization, this study employs the Local Projection method to analyze the marginal effects of RER undervaluation on labor reallocation to tradable sectors as economies become more integrated. This approach allows for a nuanced understanding of how RER policies influence economic restructuring in an integrated global market, providing valuable insights for policymakers aiming to optimize trade and exchange rate strategies to foster sustainable economic growth.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
