---
layout: page
title: Gender and Questionnaire Design
description: Using a synthetic dataset to motivate new methods for quantitatively studying gender
img: /assets/img/census_3.png
permalink: gender-questionnaire-design
importance: 3
category: Work
skills: R, research, data vis
---

* <a href="/assets/pdf/Stewart_poster_221202.pdf" target="_blank">Click here</a> to download a PDF of my poster presentation with more background and discussion.

This project culminated in a presentation and poster session in the 2022 CSDE Lightning Talks as part of my T-32 Demography and Data Science funded traineeship. The goal of this work was to illustrate the need for new methods of representing gender in demography.

I created a synthetic (i.e. fake) population with gender categories that roughly corresponded to the proportions found in the 2015 United States Transgender Survey and mock values for human height. I then selected four different question designs asking about the subjects' gender and simulated how each individual in the population would respond to each question. For example, given a multiple choice question a certain individual might respond "other" while responding "non-binary" given a free response option. I arbitrarily chose height as a familiar and relatively straightforward metric that wouldn't distract from the effects of different questionnaire designs.

<div class="col-10">
<figure style="text-align: center;">
    <img src="../../assets/img/census_2.png" title="Four different questionnaire designs" style="max-height: 30vw;"/>
    <figcaption class="caption">Illustrating how a single population might respond to four different questionnaire designs.</figcaption>
</figure>
</div>

Each of the four graphs above also show the corresponding questionnaire. The assumptions that I made to determine how my synthetic population responded to each questionnaire are as follows:

* Non-binary participants would be unable to fill out the questionnaire in Scenario A and thus are not represented in the Scenario A data.
* When shown a free response in Scenarios C and D non-binary participants would use more specific terminology. In other words, participants prefer not to describe themselves as "Other" when given the choice and may use a variety of words besides non-binary (informed by the 2015 Trans Survey). This preference explains the difference between Scenarios B and C.
* The lack of conventional male/female options in Scenario D would cause less uniformity even among those who identify solely as male or female. For example, a participant might respond as a "trans man" instead of "male" or as a "woman" instead of "female") and therefore would exhibit less agreement. 
* The “coefficient” values shown are loosely based on the male and female distributions of human height (those who are not male or female are randomly assigned to one of the two normal distributions).


Together, the four scenarios show a tradeoff between exclusion (Scenario A), group cohesion (best in Scenario B), and accurate description (best in Scenarios C and D). The assumptions I listed are, of course, incredibly crude and reductive assumptions. I don't expect these assumptions to hold up to any real-life population beyond (1) the trade-offs mentioned and (2) the small population size of explicitly trans and non-binary people relative to those who identify solely as male or female.

I enjoyed this project as it helped me communicate some of the work I've been doing in critical data studies in a way that was more appropriate for conversations in demography and data science. It also helped me sharpen my own understanding of the limits of current survey-based methods for studying gender. You can click on the PDF linked above for more context.
