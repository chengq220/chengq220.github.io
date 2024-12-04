---
layout: page
title: Drone Delivery Path Optimization
description: Optimize delivery of packages using algorithms like A*, MDP, etc.
img: assets/img/drone.jpg
importance: 1
category: other
related_publications: false
---

The growing demand for fast, reliable, and cost-effective package delivery services has created significant challenges for logistics and transportation networks. Companies must navigate complex systems involving large fleets, dynamic traffic conditions, and diverse customer demands. Traditional manual planning methods often fall short in addressing these complexities, leading to inefficiencies, increased costs, and delays. Optimizing delivery routes and schedules using advanced algorithms offers a promising solution, enabling smarter decision-making and improved operational efficiency. With the rise of e-commerce and urban congestion, the need for innovative, algorithm-driven approaches has never been more critical.

Algorithms such as A* and Markov Decision Processes (MDPs) are well-suited to tackle these challenges. A*, a heuristic-based search algorithm, efficiently finds the shortest paths in static or semi-static environments, making it ideal for real-time route optimization. Meanwhile, MDPs provide a framework for making sequential decisions under uncertainty, allowing systems to adapt dynamically to changing traffic patterns or delivery constraints. By leveraging these advanced methods, this research aims to enhance package delivery systems, reducing operational costs and delivery times while improving customer satisfaction. Furthermore, these approaches hold the potential to contribute to greener logistics by minimizing fuel consumption and reducing carbon emissions through optimized routing.

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
