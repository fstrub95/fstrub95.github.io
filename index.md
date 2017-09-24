---
layout: default
---

## Description
I am a PhD candidate at the University of Lille in the Inria SequeL team, advised by Prof. Olivier Pietquin and Jérémie Mary.
My research project explores how to enable computers to acquire language through multimodal interactions. 
Therefore, I focus my work on goal-oriented visually grounded dialogues. 
I am both developing new neural architectures to fuse vision and language modalities, and I am extending deep reinforcement learning methods to fit the dialogue setting. 
Finally, I am also studying dialogues from a multi-player Markov game perspective to develop new training algorithms.

## Selected Papers

H. de Vries &ast; , **F. Strub** &ast; , J. Mary, H. Larochelle, O. Pietquin, A. Courville <br/>
*Modulating Early visual Processing by language.* <br/>
In Proc. of NIPS (2017) - Spotlight. <br/>
[Paper](https://arxiv.org/abs/1707.00683) - [code](https://github.com/GuessWhatGame) 

**F. Strub**, H. de Vries, J. Mary, B. Piot, A. Courville, O. Pietquin <br/>
*End-to-end optimization of goal-driven and visually grounded dialogue systems.* <br/>
In Proc. of IJCAI (2017) - Oral presentation.<br/>
[Paper](https://arxiv.org/abs/1703.05423) - [code](https://github.com/GuessWhatGame/guesswhat) - [website](https://guesswhat.ai/)

## Selected Papers


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
