---
layout: page
title: Evolutionary optmisation algorithms
description: Devising evolutionary algorithms to solve optimisation problems with many-objectives.
img:
importance: 3
---

<h4> Project description: </h4>
Many real world problems involve multiple objectives to be satisfied concurrently subject to some constraints. Solution to such problems involve a set of solutions each of which can’t be improved in one objective without deteriorating in another. We say these solutions are <b>non-dominated</b> with respect to one another. <b>Evolutionary algorithms </b> are particularly suitable for solving such problems due to the property of achieving the entire set of solution in one single run.  

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
    <img width= 400 height = 300 src="{{ '/assets/img/multiopt.png' | relative_url }}" alt="" title="Multi-objective optimisation"/>
    </div>
</div>
<div class="caption"> Non-dominated solutions of a 2-objective optimisation problem using evolutionary algorithm. </div>

Problems involving more than three objectives are commonly known as <b>Many-objective Optimization Problems</b>. Since the number of non-dominated solutions increases
exponentially with increase in the number of objectives, many-objective optimisation problems are challenging to solve. The objective is to devise an algorithm for solving many-objective optimisation problems.

<h4> Contributions: </h4>
In my undergraduate thesis, in collaboration with <a href="https://sites.google.com/site/siddhartha047/"> Siddhartha Shankar Das</a>, I adopted the notion of fuzzy-dominance to solve many-objective optimisation problems. Later Siddhartha adopted the notion of reference points to develop a new algorithm that significantly improves the performance of our algorithm.   

<h4> Publication/Preprints: </h4>
If you are interested in the fuzzy-dominance based algorithm, please refer to my undergraduate thesis and poster-
   
* <a href = "https://drive.google.com/file/d/1t9gvTYnd1Olp0gUPvcMXmRjPKbm2EI5X/view?usp=sharing"> Undergraduate Thesis </a>
* Undergraduate Poster presentation, BUET: <a href = "https://drive.google.com/file/d/1TUHkIk_wcO5X7yfOrR5Qgjd4p3Ue2oJN/view?usp=sharing"> Many-Objective Evolutionary Approach using Fuzzy Dominance with Bidirectional Bias (<a href="https://drive.google.com/file/d/0B_vV1Xwwq8rlUkg4RnpybklQWjA/view?usp=sharing"> Distinguished Poster award, 2014</a>)</a> 


If you are interested in the fuzzy-dominance and reference point based algorithm, please refer to the following paper-
* <a href="https://www.sciencedirect.com/science/article/abs/pii/S2210650217304996"> Evolutionary algorithm using adaptive fuzzy dominance and reference point for many-objective optimization, Swarm and evolutionary computation (2019).</a>

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
</div>
``` -->
