---
layout: default
title: Publications
---

# Publications

## Journal Articles
<ul>
{% for pub in site.data.publications.publications %}
  <li>
    {{ pub.authors }} ({{ pub.year }}). {{ pub.title }} <i>{{ pub.venue }}</i>.
  </li>
{% endfor %}
</ul>

## Conference Presentations
<ul>
{% for pres in site.data.publications.presentations %}
  <li>
    {{ pres.authors }} ({{ pres.year }}). {{ pres.title }} <i>{{ pres.venue }}</i>.
  </li>
{% endfor %}
</ul>