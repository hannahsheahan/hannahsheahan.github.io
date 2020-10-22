---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---


# Learning Planet Taxonomies [2019]
During development, humans learn that the similarity between natural objects (e.g. plants or animals) often maps onto hierarchical structures. For example, as adults we know that canaries and ravens are both types of birds, meaning that they have wings and beaks, and are likely to have more other features in common with each other than with a donkey, which is not a bird. How do these semantic relationships develop in humans and deep networks? Saxe et al ([2019](https://www.pnas.org/content/116/23/11537)) has a decent answer for deep linear networks, so we set about trying to test some of these emergent theories in humans.

Starting with [Sebastian Lague's](https://github.com/SebLague/Procedural-Planets) repo for procedural 3D object generation in Unity, I built a planet taxonomy generator which creates arbitrarily many unique planets for perceptual learning studies, by sampling across a hierarchy of continuously valued perceptual features.

Here's a fun video of some of me varying some of these funny-looking wobbly textures:
<iframe width="280" height="157" src="https://www.youtube.com/embed/hwhLnh4Tuvw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


To give us a bigger, more complex hierarchy I also built in a few new traits, like...

- 🌋 mountain height
- 🌐 mountain spatial frequency
- ☀️ planet proximity to the sun
- 💨 atmosphere strength
- 🎨 planet colour saturation
- 🌜 mooniness (number & size of moons)
- 💫 orbital ring radius


The experimental component of this project is underway, stay tuned...

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
