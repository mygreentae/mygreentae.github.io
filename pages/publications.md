---
layout: default
permalink: /publications/
---
**[Home](/) >> Publications**

# Publications

<div class="row">
  {% for publication in site.publications | sort:'date' reverse %}
    {% include publication-card.html publication=publication %}
  {% endfor %}
</div>