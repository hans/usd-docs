---
layout: base
title:  'Finnish Relations'
generated: 'true'
---

Note: This document is a draft. Not all relations have been converted to USD-compatible description yet.

{% include fi-table.html %}

----------

Alphabetical listing

<ul>
{% for p in site.fi %}
  <li><a href="{{ p.url | remove_first:'/' }}">{{ p.title }}</a>: {{ p.shortdef }}</li>
{% endfor %}
</ul>
