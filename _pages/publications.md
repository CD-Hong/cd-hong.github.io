---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
	{% include archive-single.html %}
{% endfor %}

---
## Work in Progress

1. **Mutual Funds and Capital Flows**, with Jaewon Choi, Sebastiao Oliveira, and Jay Rafi.

---
## Research Assistant

1. **Natural Disasters and Municipal Bonds**, by Junkyung Auh, Jaewon Choi, Tatyana Deryugina, and Tim Park.