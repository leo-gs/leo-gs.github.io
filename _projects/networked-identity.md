---
layout: page
title: Networked Identity
description: Grassroots gender identities through Reddit data.
color: black
img: /assets/img/pretty_graph_black_cropped.png
importance: 1
category: Work
permalink: networked-identity
github: https://github.com/leo-gs/reddit-gender
skills: SNA, Reddit, Python, SQL, research, data vis
---

* <a href="https://dl.acm.org/doi/10.1145/3449082">My paper published in CSCW</a>
* <a href="https://github.com/leo-gs/reddit-gender">Code for data collection</a>

A lot of what we understand about gender categories stems from legal and biomedical contexts such as the categories used on drivers licenses and the medical relationship between gender and the body. In these contexts gender is static and unidimensional—we don't often think of how different gender categories relate to each other or change over time. 

The goal of this project was to use data from Reddit to understand how people relate to different gender identifiers in casual online settings. Rather than apply an existing gender taxonomy, my goal was to examine how different gender terms emerged "in the wild". I used social network analysis and snowball sampling to create a network of gendered subreddits.

<div class="col-10">
<figure style="text-align: center;">
    <img src="../../assets/img/one_step_link_network_class_colors.png" title="Link network colored by modularity class" alt="An image of a large graph. There is a large clump of nodes towards the center and smaller clumps of nodes drifting outwards towards the periphary. Groups of nodes are differentiated by color." style="max-height: 30vw;"/>
    <figcaption class="caption">A network visualization of subreddits connected by sidebar links.</figcaption>
</figure>
</div>

The image above shows a network visualization where nodes represent subreddits and edges represent links in the subreddit sidebars. For example, if r/cats were to link to r/dogs in the subreddit sidebar you would see an arrow pointing from r/cats to r/dogs on this graph. The colors here were assigned by running a Louvain clustering algorithm which helps us identify denser areas of the network. I used network visualizations like this one along with quantitative metrics to explore the contextual and historical relationships between different gendered subreddits. You can read more about this work in <a href="https://dl.acm.org/doi/10.1145/3449082">my paper published at CSCW</a>. You can also find my code for collecting data from Reddit <a href="https://github.com/leo-gs/reddit-gender">here</a> (although it may not work due to changes with the API).


