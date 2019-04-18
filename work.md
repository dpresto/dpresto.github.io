---
layout: default
title: "Work"
author: "DP"
---
<h1>Projects</h1>

<ul>
  {% for project in site.work %}
    <li>
      <h2>{{ project.title }}</h2>
      <h3>{{ project.author }}</h3>
      <p>{{ project.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
