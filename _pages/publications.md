---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


<!-- ─── Work in Progress ───────────────────────────────────────────────────── -->
<h2 class="work-section-title">Work in Progress</h2>

<ol class="work-list">
  <li>
    <a href="#">Mutual Funds and Capital Flows</a>, with Jaewon Choi, Sebastiao Oliveira, and Jay Rafi.
  </li>
  <!-- 필요하면 항목 추가
  <li>
    <a href="링크">다른 작업 제목</a>, with 공동저자들.
  </li>
  -->
</ol>

{% endfor %}