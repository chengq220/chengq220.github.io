---
layout: page
title: Drone Delivery Path Optimization
description: Optimize delivery of packages using algorithms like A*, MDP, etc.
img: assets/img/drone.jpg
importance: 1
category: other
related_publications: false
---

Motivation: The rapid growth of e-commerce, and increasing demand for faster deliveries has necessitated autonomous systems capable of efficiently and safely delivering packages. Traditional delivery methods face challenges such as traffic congestion, high costs, and limited scalability. Autonomous drones offer a promising solution, and many companies have experimented with their own autonomous delivery systems, such as the Amazon Scout. However, these systems must navigate dynamic urban environments, and plan routes that accommodate for environmental obstacles to deliver packages quickly, efficiently, and safely.


The project can be accessed at:

    ---
    https://github.com/chengq220/CS4260_FinalProject
    ---

Each agent will traverse a grid map with deliverables marked in dark blue and drop-off marked in orange. To increase the complexity of the problem, the environmnet will be dynamic which means that every few steps, the positions of obstacles and restrictions will change. The map for the game looks like the following:

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0 align-self-center">
        {% include figure.liquid loading="eager" path="assets/img/project1_map.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An example of the envrionment
</div>

Taking the above map as an example, the path that agents implemented using different algorithms took are shown below
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project1_showcase1.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project1_showcase2.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project1_showcase3.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     On the left is the path taken using A* algorithm. Middle is the path taken using MDP. Right, On the right is the path taken using CSP.
</div>
