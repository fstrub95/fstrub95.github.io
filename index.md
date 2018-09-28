---
layout: default
---

## Description
I am a PhD candidate at the University of Lille in the Inria [SequeL team](https://team.inria.fr/sequel/), advised by Prof. [Olivier Pietquin](http://www.lifl.fr/~pietquin/) and [Jérémie Mary](http://www.grappa.univ-lille3.fr/~mary/).
My research project explores how to enable computers to acquire language through multimodal interactions. 
Therefore, I focus my work on goal-oriented visually grounded dialogues. 
I am both developing new neural architectures to fuse vision and language modalities, and I am extending deep reinforcement learning methods to fit the dialogue setting. 
Finally, I am also studying dialogues from a multi-player Markov game perspective to develop new training algorithms.

<article class="more_publi">
<a href="{{ site.baseurl }}/publications" class="read-more">All publications</a>
</article>

## Workshops
I put a lot of effort in organizing quality workhsop to federate the communties around research direction. Therefore, I was involved in the organization of the following workshop
 - Visually Grounded Interaction and Language (2018) - [website](https://nips2018vigil.github.io/)
 - European Workshop of Reinforcement Learning (2018) - [website](https://ewrl.wordpress.com/ewrl14-2018/)
 - Visually Grounded Interaction and Language (2017) - [website](https://nips2018vigil.github.io/)
 - International conference of Machine Learning (2015), Local commitee - [website](https://icml.cc/2015/)

## Websites
- GuessWhat is a two-player visual dialogue game we developed. We used it as a testbed for Visually Grounding Language Machine Learning algorithms. [website](https://guesswhat.ai/)
 - LightingTorch is a website I set up when I first started to use Lua-Torch. Its initial goal was to provide helpful tips on the Lua Torch Framework. [website](http://lighting-torch.com/)


## Public presentations
 - ECCV workshop  on Visual Learning and Embodied Agents in Simulation Environments (2018) - [website](https://eccv18-vlease.github.io/)
 - Machine Learning Meetup Nantes (2017) - *The GuessWhat?! storyline* - [website](https://www.meetup.com/Nantes-Machine-Learning-Meetup/events/239908834/)
 - Meet-up Recsys Presentation (2016) - *Using Neural Networks to predict user ratings* - [website](https://www.meetup.com/RecSysFR/events/231530623/?_cookie-check=24UkbWeDEob87GeP) - [video](https://www.youtube.com/watch?v=VTpAZRlgWJk)

## Recent blog posts
<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
