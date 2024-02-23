---
layout: page
title: Quantifying Personhood
description: Qualitative methods and critical perspectives for data scientists.
img: /assets/img/quantifying_personhood_dashboard_cropped.png
importance: 2
permalink: /quantifying-personhood
category: Work
github: https://github.com/leo-gs/quantifying_personhood
skills: teaching, Reddit, Yelp, R, Shiny, data vis
---

* <a href="https://github.com/leo-gs/quantifying_personhood">Repository with data workshops and reading list</a>

The original curriculum for this course was designed in collaboration with Jaime Snyder, building on her vision of a course that introduced data science students to qualitative and design methods. I have since modified the course materials to include two data analysis workshops and an updated reading list as part of my teaching practicum. I have also shifted the design portions of the course to instead focus on critical data studies and critical quantitative methods. The goal of this course in its current form is to equip data scientists with an understanding of qualitative and critical perspectives in a way that is accessible and might complement conventional data science methods.

I am especially proud of the two data workshops I created in this project. It was an exciting challenge to develop tools that not only gave students enough freedom to engage with the material in a self-driven way but also to do so in a way that aligned with a critical data studies perspective. One underlying goal was to demonstrate that adopting a qualitative or critical perspective on data doesn't have to mean doing away with all data analysis tools—instead it means taking the time to understand their limits.

# Introductory Data Workshop

The first data workshop accompanies the Introduction week readings. In this workshop I use a subset of the <a href="https://www.yelp.com/dataset">Yelp Academic Dataset</a> that focused in bars in Philadelphia.

<div class="col-10">
<figure style="text-align: left;">
    <img src="../../assets/img/intro_dashboard.png" title="Introduction week dashboard" style="max-height: 30vw;"/>
    <figcaption class="caption">Introduction week dashboard that introduced students to asking qualitative questions.</figcaption>
</figure>
</div>

Students follow a series of prompts that ask them to compare quantitative and qualitative perspectives. The goal of this workshop is to familiarize students with close reading and the richness of qualitative data. This conceptual basis provides a foundation for the more detailed and more formal introduction to qualitative methods later in the curriculum.

# Trace Ethnography Data Workshop

The second data workshop is a primer on trace ethnography. While students are likely already familiar with trace data (i.e. using digital traces as data) they may not know it by that name and may not know how to integrate trace data into a qualitative approach. 


In addition to introduction and final reflection prompts, this workshop walks students through two activities: in "Handling Trace Data" students compare three different perspectives on Reddit posts. Students are prompted to apply concepts from their trace data readings to the Reddit data set and discuss what is revealed and what is hidden by each lens.

<figure style="text-align: left;">
<div class="row justify-content-center">
	<img src="../../assets/img/trace_eth_db_4.png" title="Trace data 'in the wild'" style="width: 20vw;"/>
	<img src="../../assets/img/trace_eth_db_2.png" title="Individual perspective" style="width: 20vw;"/>
	<img src="../../assets/img/trace_eth_db_3.png" title="Aggregate perspective" style="width: 20vw;"/>
	<figcaption class="caption">The same trace data from r/books viewed through three different lenses: "in the wild", through a micro lens where individual posts can be viewed, and through a macro aggregate lens. Posts are the top 20 posts of all time from the subreddit r/books.</figcaption>
</div>
</figure>

In the second activity, "Mixing Methods", students are shown a shared-moderator network projection where each represents a subreddit and each edge represents a user that serves as a moderator for both subreddits. The network visualization is intentionally misleading—only by a close inspection of the top moderators in the network will students discover the presence of bot accounts such as AutoModerator. Students can then remove the edges associated with bot accounts from the network visualization. The goal of this activity is to illustrate how qualitative methods like trace ethnography can strengthen data science work. Students learn to immerse themselves in the data from the perspective of the data subjects.

<div class="col-10">
<figure style="text-align: left;">
    <img src="../../assets/img/trace_network_2.png" title="Network visualization from trace ethnography workshop" style="max-height: 30vw;"/>
    <figcaption class="caption">An interactive network visualization from the "Mixing Methods" activity in the trace ethnography workshop. Nodes represent the top 100 subreddits at the time of data collection. Edges represent the shared moderators between pairs of subreddits.</figcaption>
</figure>
</div>

The images shown here are static images—the interactive versions of these visualizations can be accessed by downloading the linked repository and running the Shiny app locally in R Studio.