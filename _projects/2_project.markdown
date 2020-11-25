---
layout: page
title: Topological data analysis
description: 'Approximating Persistence homological features using \(\epsilon\)-net and lazy witness complex'
# img: /assets/img/3.jpg
importance: 2
---
<h4>Motivation: </h4> 
<a href = "https://en.wikipedia.org/wiki/Topological_data_analysis">Topological data analysis</a> computes and analyses topological features of the point clouds by constructing and studying a <a href="https://en.wikipedia.org/wiki/Simplicial_complex"> simplicial representation</a> of the underlying topological structure. The enthusiasm that followed the initial successes of topological data analysis was curbed by the computational cost of constructing such simplicial representations. The lazy witness complex is a computationally feasible approximation of the underlying topological structure of a point cloud. It is built in reference to a subset of points, called landmarks, rather than considering all the points as in the <a href="https://en.wikipedia.org/wiki/Vietoris%E2%80%93Rips_complex">Vietoris-Rips complexes</a>. 

<hr>

<h4> Contributions: </h4>
In collaboration with <a href = "https://debabrota-basu.github.io/">Debabrota Basu</a> and <a href="https://www.comp.nus.edu.sg/~steph/"> Stephane Bressan</a>, I adopt the notion of <a href="https://en.wikipedia.org/wiki/Cover_(topology)">cover </a> to define $$\epsilon$$-net. We prove that $$\epsilon$$-net, as a choice of landmarks, is an $$\epsilon$$-approximate representation of the point cloud in <a href="https://en.wikipedia.org/wiki/Hausdorff_distance">Hausdorff metric</a>. More importantly, the induced lazy witness complex is a $$3$$-approximation of the induced Vietoris-Rips complex. The implication of this result is that, persistence of topological features computed using $$\epsilon$$-net as landmark is guaranteed to deviate no more than $$\log(3)$$ away (in <a href="http://gudhi.gforge.inria.fr/doc/latest/group__bottleneck__distance.html">Bottleneck distance</a>) from the same computed using Vietoris-Rips. Finally, we propose three algorithms to construct $$\epsilon$$-net of a point cloud.

In a subsequent paper, we extended our results on graph data. A new bound on the size of $$\epsilon$$-net of a connected unweighted graph is given.
<hr>
<h4> Publication/Preprints: </h4>
If you are interested in the details, please refer to my following papers-
* <a href = "https://link.springer.com/chapter/10.1007/978-3-030-27618-8_28">Topological Data Analysis with $$\epsilon$$-net Induced Lazy Witness Complex, DEXA 2019.<a> 
* <a href = "https://arxiv.org/pdf/2009.13071.pdf" > $$\epsilon$$-net Induced Lazy Witness Complexes on Graphs, ATDA workshop, ECML-PKDD 2019. </a>

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

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
</div> -->
<!-- ``` -->
