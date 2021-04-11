---
title: "Projects"
permalink: /projects/
author_profile: true
---

## [Number lines (2020)](https://github.com/hannahsheahan/context_magnitude)

Humans can think and reason in ways that abstract over the physical properties of the world. For example, we understand that cheetahs and space rockets can both move “fast” even though animals and vehicles belong in different semantic categories, cheetahs and rockets move at vastly different absolute speeds, and they do not look alike. Learning abstract concepts such as "fast" can be challenging when relational patterns (such as relative speed) are shared across contexts but exist on different physical scales. Here, we trained humans (thanks to the wonderful Fabrice Luyckx) and recurrent neural networks to perform a magnitude comparison task, for which it was advantageous to generalise concepts of “more” or “less” between contexts. We analysed human brain signals and RNN hidden unit activity and observed that both systems developed parallel neural “number lines” for each context. In both model systems, these number state spaces were aligned in a way that explicitly facilitated generalisation of relational concepts (more and less).

Here's an example of the activations learned by some of our RNNs. You'll see each 'number line' is a similar length despite spanning different ranges in each context.
<iframe width="560" height="315" src="https://www.youtube.com/embed/8AnkExL8_so" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## [Learning Planet Taxonomies (2019)](https://github.com/hannahsheahan/HCategoryLearn)
As kids, humans learn that the similarity between objects (e.g. plants or animals) often map onto hierarchical structures. For example, as adults we know that canaries and ravens are both types of birds, and so are likely to have more features in common with each other than with a donkey, which is not a bird. How does knowledge of these semantic relationships develop in humans and deep networks? Saxe et al ([2019](https://www.pnas.org/content/116/23/11537)) has a decent answer for deep linear networks, so we set about trying to test some of these emergent theories in humans. Starting with [Sebastian Lague's](https://github.com/SebLague/Procedural-Planets) repo for procedural 3D object generation in Unity, I built a planet taxonomy generator which creates arbitrarily many unique planets for perceptual learning studies, by sampling across a hierarchy of continuously valued perceptual features.

Here's a video of me varying some parameters (astronomers, forgive me).
<iframe width="560" height="315" src="https://www.youtube.com/embed/hwhLnh4Tuvw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



To give us a more complex hierarchy I built in a few new traits...

- 🌋 mountain height
- 🌐 mountain spatial frequency
- ☀️ planet proximity to the sun
- 💨 atmosphere strength
- 🎨 planet colour saturation
- 🌜 mooniness (number & size of moons)
- 💫 orbital ring radius


## [Four Rooms (2019)](https://github.com/hannahsheahan/FourRooms2D)

Here's an example trial from a learning experiment I designed (with Chris Summerfield) and built in which human players have to search for particular rewards, like cheese or martinis. Human players have to take turns with an artificial agent when they are searching, so playing this game is not as straightforward as it looks!
With practice, players learn that there are patterns to where different reward types are likely to be found, and players can use these rules to find the rewards faster (and get more points!).

I collected a large behavioural dataset of people playing this game from all over the world (via Amazon mturk) as well as a neural dataset in which people played this game in an fMRI machine. We're currently analysing the neural data (with Paul Muhle-Karbe) to understand a bit more about how the brain can learn and implement abstract spatial rules.

<iframe width="560" height="315" src="https://www.youtube.com/embed/0KNKnbZFj1Q" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
