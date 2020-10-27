---
title: "Projects"
permalink: /projects/
author_profile: true
---

This page is currently under development.

## [Number lines (2020)](https://github.com/hannahsheahan/context_magnitude)

Description under development...

## [Learning Planet Taxonomies (2019)](https://github.com/hannahsheahan/HCategoryLearn)
As kids, humans learn that the similarity between objects (e.g. plants or animals) often map onto hierarchical structures. For example, as adults we know that canaries and ravens are both types of birds, and so are likely to have more features in common with each other than with a donkey, which is not a bird. How does knowledge of these semantic relationships develop in humans and deep networks? Saxe et al ([2019](https://www.pnas.org/content/116/23/11537)) has a decent answer for deep linear networks, so we set about trying to test some of these emergent theories in humans.

Starting with [Sebastian Lague's](https://github.com/SebLague/Procedural-Planets) repo for procedural 3D object generation in Unity, I built a planet taxonomy generator which creates arbitrarily many unique planets for perceptual learning studies, by sampling across a hierarchy of continuously valued perceptual features.

Here's a fun video of some of me varying some of these wobbly textures (astronomers, forgive me).
<iframe width="560" height="315" src="https://www.youtube.com/embed/hwhLnh4Tuvw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



To give us a bigger, more complex hierarchy I also built in a few new traits, like...

- 🌋 mountain height
- 🌐 mountain spatial frequency
- ☀️ planet proximity to the sun
- 💨 atmosphere strength
- 🎨 planet colour saturation
- 🌜 mooniness (number & size of moons)
- 💫 orbital ring radius


The experimental component of this project is underway with the help of Yinan Cao.


## [Four Rooms (2019)](https://github.com/hannahsheahan/FourRooms2D)

Here's an example trial from a learning experiment I designed (together with Chris Summerfield) and built in which human players have to search for particular rewards, like cheese or martinis, across four rooms. Participants have to take turns with an artificial agent when they are searching, so its not as straightforward as it looks! With practice players learn that different reward types covary in their locations across the rooms, and can use this to maximize their points.
We have a massive neural dataset with people playing this game in an fMRI machine, which we're analysing to understand a bit more about how the brain can learn and implement abstract rules.

<iframe width="560" height="315" src="https://www.youtube.com/embed/0KNKnbZFj1Q" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## [Factorising Grid Cells (2019)](https://github.com/hannahsheahan/gridSimulations)

Description under development...


## [Uniturk (2018)](https://github.com/hannahsheahan/UniturkNav)

Description under development...

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
