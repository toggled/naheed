---
layout: page
title: Topological data analysis
description: 'Approximating Persistence homological features using \(\epsilon\)-net and lazy witness complex'
# img: /assets/img/3.jpg
importance: 2
category: PhD
giscus_comments: true
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
