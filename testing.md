---
layout: page
title: Тестовый заголовок
permalink: /testing/
---

<div class="post-grid">
  {%- for post in site.posts -%}
    {% include post-card.html %}
  {%- endfor -%}
</div>