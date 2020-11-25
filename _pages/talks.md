---
layout: page
permalink: /talks/
title: talks
description: Slides for various Research talks and Guest lectures.
nav: true
---
<div class = "post">
    <header class = "post-header"> 
        <h4 class="post-title">Guest lectures</h4>
        <ul class="list-group">
            <li class="list-group-item list-group-item-action list-group-item-secondary"> Big Data Techniques and Technologies (BT4221), 2020
                <ul>
                    <li> <b> Using Amazon EMR to run spark applications. </b>  (<a href="#">Slides</a>)</li>
                    <li> <b> Practical machine learning using Amazon Sagemaker services</b> (<a href="#">Slides</a>) </li>
                </ul>
            </li>
            <li class="list-group-item list-group-item-action list-group-item-secondary"> Data Management and Warehousing (BT5110), 2019
                <ul>
                    <li> <b> Building a retail sales data mart using Pentaho Data Integration tool</b> (<a href="https://drive.google.com/drive/folders/1sEieIecDvBtizmvxsHGaENmpk8GvHJma?usp=sharing">Slides, Datasets and Kettle transformation files</a>) </li>
                </ul>
            </li>
            <li class="list-group-item list-group-item-action list-group-item-secondary"> Information visualisation (CS5246), 2018
                <ul> 
                    <li> <b>Graph and Hypergraph visualisation</b>. (<a href="{{ '/assets/pdf/viz_talk.pdf' | relative_url }}">Slides</a>)</li>
                </ul>
            </li>
        </ul>
    </header> 
</div>
<hr>
<div class = "post">
    <header class = "post-header"> 
        <h4 class="post-title">Research talks</h4>
        <ul class="list-group">
            <li class="list-group-item list-group-item-action list-group-item-secondary"> DEXA 2020 talk on <b>Constructing and Generating Random hypergraphs with prescribed degree and dimension sequences</b> (<a href="{{ '/assets/pdf/dexa20talk.pdf' | relative_url }}">Slides</a>)</li>
            <li class="list-group-item list-group-item-action list-group-item-secondary"> ATDA 2019 3min-talk on <b> \(\epsilon\)-net induced lazy witness complexes on Graphs</b> (<a href="{{ '/assets/pdf/atda_3min.pdf' | relative_url }}">Slides</a>)</li>
            <li class="list-group-item list-group-item-action list-group-item-secondary"> DEXA 2019 talk on <b>Topological data analysis using \(\epsilon\)-net induced lazy witness complex</b> (<a href="{{ '/assets/pdf/dexa19talk.pdf' | relative_url }}">Slides</a>)</li>
            <li class="list-group-item list-group-item-action list-group-item-secondary"> DEXA 2017 talk on <b>Hypergraph drawing using force-directed placement</b> (<a href="{{ '/assets/pdf/dexa17talk.pdf' | relative_url }}">Slides</a>)</li>
            <li class="list-group-item list-group-item-action list-group-item-secondary"> E2S2-CREATE seminar (2018) talk on <b> Topological data analysis </b> (<a href="{{ '/assets/pdf/Create_Talk_TDA.pdf' | relative_url }}">Slides</a>)</li>
        </ul>
    </header>
</div>

<!-- <div class="projects grid">

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

</div> -->