---
layout: page
title: Projects
permalink: /projects/
---

These projects are independently developed and maintained by the members and volunteers of the Kashi Code Collective.

<ul class="project-list">
{%- for project in site.data.projects -%}
  <li>
    <a href="{{ project.url }}"><strong>{{ project.name }}</strong></a>
    <span>{{ project.description }}</span>
    <br>
    <span><strong>Maintainer:</strong> {{ project.maintainer }}</span>
  </li>
{%- endfor -%}
</ul>
