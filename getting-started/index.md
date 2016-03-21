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
      <img src="" alt="teaser" itemprop="image">
      {{ member.name }}
    </a>
    <p class="entry-date date published">{{ member.date }}</p>
  </article>
{% endfor %}

  <article class="tile" itemscope="" itemtype="http://schema.org/Article">
  <a href="//psurya1994.github.io/Personal-Website//articles/syntax-highlighting-test/" title="Syntax Highlighting Test" class="post-teaser"><img src="//psurya1994.github.io/Personal-Website//images/400x250.gif" alt="teaser" itemprop="image"></a>
  <p class="entry-date date published"><time datetime="2014-11-30" itemprop="datePublished">November 30, 2014</time></p>
  <h2 class="post-title" itemprop="name"><a href="//psurya1994.github.io/Personal-Website//articles/syntax-highlighting-test/">Syntax Highlighting Test</a></h2>
  <p class="post-excerpt" itemprop="description">Demo post to test the various ways of using syntax highlighting.</p>
</article>


</div>
<!-- /.tiles -->

      </div><!-- /.page-content -->
    </div><!-- /.archive-wrap -->
  </div><!-- /.wrap -->
</div>