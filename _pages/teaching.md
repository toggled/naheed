---
layout: page
permalink: /teaching/
title: teaching
description: Courses I have taught over the years.
nav: true
nav_order: 6
---

<!-- For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.

Organize your courses by years, topics, or universities, however you like! -->

<div class="projects grid">

  {% assign sorted_projects = site.teachings | sort: "importance" %}
  {% for project in sorted_projects %}
  <div class="grid-item">
    {% if project.redirect %}
    <a href="{{ project.redirect }}" target="_blank">
    {% else %}
    <a href="{{ project.url | relative_url }}">
    {% endif %}
      <div class="card hoverable">
        {% if project.img %}
        <img src="{{ project.img | relative_url }}" alt="project thumbnail">
        {% endif %}
        <div class="card-body">
          <h2 class="card-title">{{ project.title }}</h2>
          <p class="card-text">{{ project.description }}</p>
        </div>
      </div>
    </a>
  </div>
{% endfor %}

</div>


<!-- <div class="post">

  <header class="post-header">
    <h1 class="post-title">Guest lectures</h1>
    <p class="post-description">Guest lectures I have given over the years</p>
  </header>

  <article>

<div class="projects grid" style="position: relative; height: 367.625px;">

  
  
  <div class="grid-item" style="position: absolute; left: 0px; top: 0px;">
    
    <a href="/naheed/teachings/NUS/">
    
      <div class="card hoverable">
        
        <img src="/naheed/assets/img/3.jpg" alt="project thumbnail">
        
        <div class="card-body">
          <h2 class="card-title">Courses at NUS</h2>
          <p class="card-text">Approximating Persistence homological features using <mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" role="presentation" tabindex="0" ctxtmenu_counter="0" style="font-size: 119.4%; position: relative;"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D716 TEX-I"></mjx-c></mjx-mi></mjx-math><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>ϵ</mi></math></mjx-assistive-mml></mjx-container>-net and lazy witness complex</p>
        </div>
      </div>
    </a>
  </div>

  <div class="grid-item" style="position: absolute; left: 260px; top: 0px;">
    
    <a href="/naheed/teachings/UIU/">
    
      <div class="card hoverable">
        
        <img src="/naheed/assets/img/12.jpg" alt="project thumbnail">
        
        <div class="card-body">
          <h2 class="card-title">Courses at UIU</h2>
          <p class="card-text">Generating random hypergraph with a given degree and dimension contraints</p>
        </div>
      </div>
    </a>
  </div>


</div>

  </article>

</div> -->