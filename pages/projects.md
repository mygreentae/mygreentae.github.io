---
layout: default
permalink: /projects/
---

**[Home](/) >> Projects**

# Projects

<div class="row">
  {% assign sorted_projects = site.projects | sort: 'date-started' | reverse %}
  {% for project in sorted_projects %}
    {% include project-card.html project=project %}
  {% endfor %}
</div>