---
layout: page
title: Random hypergraphs
description: 'Generating random hypergraph with a given degree and dimension contraints'
# img: /assets/img/12.jpg
importance: 1
category: PhD
# related_publications: einstein1956investigations, einstein1950meaning
---
<h4>Motivation:</h4> Given a degree sequence and dimension sequence, how to estimate some property of the set of hypergraphs conforming to the given sequences?

* <b>Example:</b>
There are three hypergraphs that conform to degree sequence $$(a)_n = (3,2,2,2)$$ and dimension sequence $$(b)_n = (4,3,3)$$.
<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/confighg.svg' | relative_url }}" alt="" title="Hypergraphs with a given degree and dimension sequence"/>
<!-- <div class="caption"> Hypergraphs with degree sequence (a)_n = (3,2,2,2) and dimension sequence $$(b)_n = (4,3,3)$$</div> -->

The objective is to estimate mean of some property \(f\) of the set of conforming hypergraphs. 
<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/appl1.svg' | relative_url }}" alt="" title="Estimating properties of the set of conforming hypergraphs"/>

In order to do so, one needs to first, generate random hypergraphs as samples and finally, devise a statistical estimator to estimate the population mean of \(f\) from the sample hypergraphs.
<hr>
<h4> Contributions: </h4>
In collaboration with <a href = "https://debabrota-basu.github.io/">Debabrota Basu</a>, <a href="https://www.comp.nus.edu.sg/~steph/"> Stephane Bressan</a> and <a href="http://decreusefond.telecom-paristech.fr/wordpress/"> Laurent Decrausefond</a>, I developed algorithms for generating random hypergraphs conforming to given degree and dimension sequences. I also devised an <a href="https://en.wikipedia.org/wiki/Importance_sampling"> Importance sampling </a> based estimator for estimating properties of such hypergraphs.
<hr>
<h4> Publication/Preprints: </h4>
If you are interested in the details, please refer to my following papers-
* <a href = "https://link.springer.com/chapter/10.1007/978-3-030-59051-2_9">Construction and Random Generation of Hypergraphs with Prescribed Degree and Dimension Sequences, DEXA 2020.<a> 
* <a href = "https://arxiv.org/pdf/2004.05429.pdf" > ArXiv preprint (Full version) </a>