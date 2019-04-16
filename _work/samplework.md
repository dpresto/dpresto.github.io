---
layout: post
title: "Sample Project"
author: "DP"
published: true
post_image: /assets/interview_setup.png
post_cap: Image courtesy of Nicolas Coia
alt_post_image: A photo of a home office reconfigured for a remote interview
---

Yup

{% for title in site.work %}
  <h2>
    <a href="{{ work.url }}">
      {{ work.title }}
    </a>
  </h2>
  <p>{{ work.content | markdownify }}</p>
{% endfor %}
