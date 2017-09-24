---
layout: default
---

## Description
I am a PhD candidate at the University of Lille in the Inria [SequeL team](https://team.inria.fr/sequel/), advised by Prof. [Olivier Pietquin](http://www.lifl.fr/~pietquin/) and [Jérémie Mary](http://www.grappa.univ-lille3.fr/~mary/).
My research project explores how to enable computers to acquire language through multimodal interactions. 
Therefore, I focus my work on goal-oriented visually grounded dialogues. 
I am both developing new neural architectures to fuse vision and language modalities, and I am extending deep reinforcement learning methods to fit the dialogue setting. 
Finally, I am also studying dialogues from a multi-player Markov game perspective to develop new training algorithms.

## Selected Papers

H. de Vries\*; , **F. Strub**\*; , J. Mary, H. Larochelle, O. Pietquin, A. Courville <br/>
*Modulating Early visual Processing by language.* <br/>
In Proc. of NIPS (2017) - Spotlight. <br/>
[Paper](https://arxiv.org/abs/1707.00683) - [code](https://github.com/GuessWhatGame) 

**F. Strub**, H. de Vries, J. Mary, B. Piot, A. Courville, O. Pietquin <br/>
*End-to-end optimization of goal-driven and visually grounded dialogue systems.*  <br/>
In Proc. of IJCAI (2017) - Oral presentation.  <\br>
[Paper](https://arxiv.org/abs/1703.05423) - [code](https://github.com/GuessWhatGame/guesswhat) - [website](https://guesswhat.ai/)

<article class="more_publi">
<a href="{{ site.baseurl }}/publications" class="read-more">All publications</a>
</article>


## Websites
GuessWhat is a two-player visual dialogue game we developed. We used it as a testbed for Visually Grounding Language Machine Learning algorithms. <br/>
[website](https://guesswhat.ai/)

LightingTorch is a website I set up when I first started to use Lua-Torch. Its initial goal was to provide helpful tips on the Lua Torch Framework. <br/>
[website](http://lighting-torch.com/)


## Presentations
2018 (to come) Machine Learning Meetup Nantes <br/>
*The GuessWhat?! storyline* <br/>
[website](https://www.meetup.com/Nantes-Machine-Learning-Meetup/events/239908834/)

2016 - Meet-up Recsys Presentation <br/>
*Using Neural Networks to predict user ratings* <br/>
[website](https://www.meetup.com/RecSysFR/events/231530623/?_cookie-check=24UkbWeDEob87GeP) - [video](https://www.youtube.com/watch?v=YSBNUZIV7ZM)

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
