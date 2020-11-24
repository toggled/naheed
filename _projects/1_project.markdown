---
layout: page
title: Random hypergraphs
description: 'Generating random hypergraph with a given degree and dimension contraints'
img: /assets/img/12.jpg
importance: 1
---
<h4>Motivation:</h4> Given a degree sequence and dimension sequence, how to estimate some property of the set of hypergraphs conforming to the given sequences?

* <b>Example:</b>
There are three hypergraphs that conform to degree sequence $$(a)_n = (3,2,2,2)$$ and dimension sequence $$(b)_n = (4,3,3)$$.
<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/confighg.svg' | relative_url }}" alt="" title="Hypergraphs with a given degree and dimension sequence"/>
<!-- <div class="caption"> Hypergraphs with degree sequence (a)_n = (3,2,2,2) and dimension sequence $$(b)_n = (4,3,3)$$</div> -->

The objective is to estimate mean of some property \(f\) of the set of conforming hypergraphs. 
<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/appl1.svg' | relative_url }}" alt="" title="Estimating properties of the set of conforming hypergraphs"/>

In order to do so, one needs to first, generate random hypergraphs as samples and finally, devise a statistical estimator to estimate the population mean of \(f\) from the sample hypergraphs.

<h4> Contributions: </h4>
In collaboration with <a href = "https://debabrota-basu.github.io/">Debabrota Basu</a>, <a href="https://www.comp.nus.edu.sg/~steph/"> Stephane Bressan</a> and <a href="http://decreusefond.telecom-paristech.fr/wordpress/"> Laurent Decrausefond</a>, I developed algorithms for generating random hypergraphs conforming to given degree and dimension sequences. I also devised an <a href="https://en.wikipedia.org/wiki/Importance_sampling"> Importance sampling </a> based estimator for estimating properties of such hypergraphs.

<h4> Publication/Preprints: </h4>
If you are interested in the details, please refer to my following papers-
* <a href = "https://link.springer.com/chapter/10.1007/978-3-030-59051-2_9">Construction and Random Generation of Hypergraphs with Prescribed Degree and Dimension Sequences, DEXA 2020.<a> 
* <a href = "https://arxiv.org/pdf/2004.05429.pdf" > ArXiv preprint (Full version) </a>

<!-- <div class="caption"> Hypergraphs with a given degree and dimension sequence </div> -->

<!-- To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/1.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/3.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/" target="_blank">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
```  -->
