---
layout: gallery
title: "Work"
author: "DP"
permalink: /work/
---
<h1>Projects</h1>

<ul>
  {% for project in site.work %}
    <li>
      <h2>{{ work.title }}</h2>
      <h3>{{ work.author }}</h3>
      <p>{{ work.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
