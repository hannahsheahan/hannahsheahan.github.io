---
permalink: /
title: ""
#excerpt: "About me"
author_profile: true
redirect_from:
  - /research/
  - /research.html
---

I am currently a Postdoc at the University of Oxford. In June 2021 I will be starting as a Research Engineer at [DeepMind](http://deepmind.com) in London. I am interested in embodied learning, generalisation and the effects of context and task structure on learning in humans and neural network models.

On the side, I'm also a Research Associate of [Wadham College](https://www.wadham.ox.ac.uk/), where I organise [talks](https://www.wadham.ox.ac.uk/about-wadham/wadhams-people/research-associates) on topics I care about like climate change, Oxford's uncomfortable colonial past, and the intersection of psychology and AI. I did my PhD at the [Computational and Biological Learning Lab](http://learning.eng.cam.ac.uk/Public/) at the University of Cambridge. Prior to that I did an undergraduate degree in engineering.


Research
------

### Learning relational structure
Psychologists use the term 'structure learning' to describe how humans learn invariances over relational patterns in data. For example, the concept we call *magnitude* describes a structure that relates stimuli to each other along a single dimension. Abstracting the relationships between stimuli across contexts permits new inferences, such as knowing that both cheetahs and space rockets move 'fast', even though animals and vehicles belong in different semantic categories, do not look alike and move at different speeds. How do humans and neural networks learn abstract knowledge of simple relational structures like magnitude? How does action impact or afford the learning of spatial or more abstract relations between things? I've been trying to answer some of these questions with [Chris Summerfield](https://www.psy.ox.ac.uk/team/christopher-summerfield) at Oxford University. Here is a short 3 minute talk from the 2021 Oxford Neuroscience Symposium where I talk about some of this work.

<iframe width="560" height="315" src="https://www.youtube.com/embed/c6FNHgxBbYI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Learning theory
What principles underlie learning in neural network models and how can we understand them? What makes some things easy to learn and other things hard? Can we predict learning dynamics? Can these tools enable us to predict the geometry of neural representations in animals performing different tasks?

### Learning perceptual hierarchies
As kids, humans learn that the similarity between objects (e.g. plants or animals) often map onto hierarchical structures. For example, as adults we know that canaries and ravens are both types of birds, and so are likely to have more features in common with each other than with a donkey, which is not a bird. How does knowledge of these semantic relationships develop in humans and deep networks? We set about trying to test some theories from structure emergence in deep networks, in humans. Starting with [Sebastian Lague's](https://github.com/SebLague/Procedural-Planets) repo for procedural 3D object generation in Unity, we built a planet taxonomy generator which creates arbitrarily many unique planets for perceptual learning studies, by sampling across a hierarchy of continuously valued perceptual features.

Here's a video of me varying some parameters (astronomers, forgive me).
<iframe width="560" height="315" src="https://www.youtube.com/embed/hwhLnh4Tuvw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


### Learning to navigate in structured worlds
Here's an example trial from a learning experiment we designed in which human players have to search a hierarchical, spatial environment for particular rewards, like cheese or martinis. Human players have to take turns with an artificial agent when they are searching, so playing this game is not as straightforward as it looks!
With practice, players learn that there are patterns to where different reward types are likely to be found, and players can use these rules to find the rewards faster (and get more points!).

We are currently working with a a large behavioural dataset of people playing this game from all over the world, as well as a neural dataset in which people played this game in an fMRI scanner. We hope to understand a little bit more about how humans learn and implement abstract spatial rules.

<iframe width="560" height="315" src="https://www.youtube.com/embed/0KNKnbZFj1Q" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


### Motor learning & control
How do we humans learn and adapt our movements as we experience the world? And how do we learn and parcellate lots of different motor skills, without overwriting others? Here's [a cute video](https://zuckermaninstitute.columbia.edu/brain-science-baseball) illustrating some of my PhD work on this topic with Daniel Wolpert (then at Cambridge University).

<iframe width="560" height="315" src="https://www.youtube.com/embed/QWaUyTiukKI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
