---
layout: default
---
<small>{{ page.date | date: "%-d %B %Y" }}</small>
<h1>{{ page.title }}</h1>

<p class="view">написал {{ page.author | default: site.author }}</p>

{{ content }}

{% if page.tags %}
  <small>тэги: <em>{{ page.tags | join: ", " }}</em></small>
{% endif %}