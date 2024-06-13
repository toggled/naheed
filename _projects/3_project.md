---
layout: page
title: Visualising hypergraphs
description: 'Force-directed drawing of hypergraphs'
# img: /assets/img/7.jpg
# redirect: https://unsplash.com
importance: 3
category: PhD
---

<h4>Motivation: </h4> 
<p>Datapoints in many real-world dataset are not necessarily dyadic in nature, e.g. relation between authors in a scientific article. 
Hypergraphs are generalisation of graphs that can naturally represent such data.</p>
A <b>hypergraph</b> consists of a collection of points called <b>vertices</b> and a collection of subset of those vertices called <b>hyperedges</b>. 

<hr>
<h4> Contributions: </h4>
<!-- <p> In order to visualise such data, we propose algorithms for drawing hypergraphs in 2D. In order to quantitatively measure quality of the visualisation we propose metrics.</p> -->

<p> Under the supervision of <a href="https://www.comp.nus.edu.sg/~steph/"> Stephane Bressan</a>, I implemented <a href = "https://github.com/toggled/Hypervis"> Hypervis</a>, a platform for drawing hypergraphs using Fructherman-Reingolds force-based graph drawing algorithm. Currently it supports subset-based, edge-based and zykov-based drawing. </p>

<div class = "caption"> Here is a demo of Hypervis. </div>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/16iXlXGsUf4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen> </iframe>

<hr>

<h4> Publication/Preprints: </h4>
If you are interested in the details, please refer to my paper-
* <a href="https://link.springer.com/chapter/10.1007/978-3-319-64471-4_31"> Hypergraph drawing by force-directed placement, DEXA 2020.</a>
<hr>
<h4> Source code: </h4>
* <a href = "https://github.com/toggled/Hypervis"> Hypervis </a> 
