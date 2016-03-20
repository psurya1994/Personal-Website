---
layout: article
title: "Getting Started with Skinny Bones"
date: 2014-06-25T13:57:25-04:00
modified: 2016-01-19
excerpt:
tags: []
image:
  feature:
  teaser:
  thumb:
share: false
---

<ul>
{% for member in site.data.online_courses %}
  <li>
      {{ member.name }}
  </li>
{% endfor %}
</ul>