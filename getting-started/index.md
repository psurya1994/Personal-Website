---
layout: default
title: "Online Courses"
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


<div id="main" role="main">     
  <div class="wrap">
    
    <div class="page-title">
      <h1>Articles</h1>
      <h2>A collection of thoughts, inspiration, mistakes, and other minutia.</h2>
    </div>
    <div class="archive-wrap">
      <div class="page-content">
        <div class="tiles">

{% for member in site.data.online_courses %}
  <article class="tile" itemscope="" itemtype="http://schema.org/Article" >
    <a href="" title="{{ member.name }}" class="post-teaser">
      <img src="{{ member.image_url }}" alt="teaser" itemprop="image">
    </a>
    <p class="entry-date date published">{{ member.date }}</p>
    <h2 class="post-title" itemprop="name"><a href="{{ member.website }}">{{ member.name }}</a></h2>
    <p class="post-excerpt" itemprop="description">{{ member.description }}</p>
  </article>
{% endfor %}


</div>

      </div><!-- /.page-content -->
    </div><!-- /.archive-wrap -->
  </div><!-- /.wrap -->
</div>