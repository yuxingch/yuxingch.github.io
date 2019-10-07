---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Applied Mathematics and B.A. in Linguistics and Computer Science, University of California, Los Angeles, 2013-2017
* M.S. in Symbolic Systems Program, Stanford University, 2017-2019

Work experience
======
* Machine Learning Engineering Intern | June 2018 - September 2018, San Francisco, CA
  * [Hoodline](https://hoodline.com)
  * Focus: Computer Vision, Natural Language Processing

Research experience
======
* Individual Research | October 2018 - Current, Stanford, CA
  * [Stanford ALPS Lab](http://alpslab.stanford.edu)
  * Implicature strength
  * Probing the pragmatic information encoded in neural networks' word embedding space (<span style="color:FireBrick;">master's thesis</span>)
    * Primary advisor: [Judith Degen](https://sites.google.com/site/judithdegen/)
    * Second reader: [Christopher Potts](https://web.stanford.edu/~cgpotts/)

Projects
======
* Automatic Detection of Dialectal Changes across Regions on Social Media \[[revised paper](https://arxiv.org/abs/1910.01818)\]\[[code](https://github.com/yuxingch/DialectGram)\]\[[demo](https://yuxingch.github.io/DialectGram/demo/main.html)\]
  * CS 224U: Natural Language Understanding, April 2019 - June 2019, Stanford Univeristy
  * <span style="color:Sienna;">Revised version of the paper has been accepted to the **Society for Computation in Linguistics** ([SCiL](https://blogs.umass.edu/scil/)) with **oral presentation** and will be published by the Association for Computational Linguistics (ACL)</span>.

* An Extension on RSA Model: Lexical Uncertainty Model \[[code](https://github.com/yuxingch/Lexical-Uncertainty-RSA)\]\[[report](https://yuxingch.github.io/files/lexical_uncertainty_rsa.pdf)\]
  * LINGUIST 230A: Introduction to Semantics and Pragmatics, January 2019 - March 2019, Stanford University
  * In this project, our focus is on the understanding of utterance and how we can construct computational models to formalize the inferences about meaning in context as well as the reasoning about the two rational agents, the pragmatic speaker and the pragmatic listener, which will be defined later. The guiding idea is the Rational Speech Acts (RSA) model proposed by [Goodman and Frank (2016)](http://langcog.stanford.edu/papers_new/goodman-2016-tics.pdf). More specifically, in this project, I'm going to explore and implement an extension of our current RSA model, focusing on the study of the lexical uncertainty associated with embedded implicatures.

* Generative Image Inpainting Models \[[poster](https://yuxingch.github.io/files/cs236_poster.pdf)\]
  * CS 236: Deep Generative Models, September 2018 – December 2018, Stanford University
  * Filling in the holes of an incomplete image with reasonable content, often referred to as image inpainting or completion, is a very important task in computer vision. It has many applications in image rendering, editing and computational photography. For instance, it could be a critical step in removal of unwanted objects from an image or reconstruction of occluded regions in image-based 3D scenes. However, although many approaches have been proposed, inpainting still remains a very challenging task. The key issue is that we need an effective way to synthesize pixels that are visually realistic, semantically plausible and coherent globally with existing portion of the image all at the same time.

* Text to Artistic Image Generation using GANs \[[report](https://yuxingch.github.io/files/text_to_artistic_image.pdf)\]\[[poster](https://yuxingch.github.io/files/CS231N_Poster.pdf)\]
  * CS 231N: Convolutional Neural Networks for Visual Recognition, April 2018 – June 2018, Stanford University
  * Generating images from texts has been a trending research topic in computer vision. Style transferring between photos and artwork is also a popular subfield. We build an application that combines these two, which allows the user to not only generate ordinary photo-like images from sentences, but also get the certain artistic style of images specified by the user.

* BiDAF-inspired Preferential Multi-perspective Matching for Question Answering Task \[[code](https://github.com/yuxingch/SQuAD-kyuych17)\]\[[report](https://yuxingch.github.io/files/BiDAF_MPM_QA.pdf)\]\[[poster](https://yuxingch.github.io/files/BiDAF_MPM_QA_poster.pdf)\]
  * CS 224N: Natural Language Processing with Deep Learning, January 2018 - March 2018, Stanford University
  * We combine the ideas of two high-performing SQuAD models, Bidirectional Attention Flow (BiDAF) and Bilateral Multi-Perspective Matching (BiMPM), and propose a new framework, BiDAF-inspired Preferential Multi-perspective Matching (BPMPM) for the question answering task. In particular, we consider multiple strategies when matching context and question embeddings in both Context-To-Question and Question-To-Context directions, apply a preferential rule when aggregating their results and aim for a more comprehensive view of the interaction between two sequences. We further refine the model using character-level embeddings in the Encoder Layer to better handle out-of-vocabulary words, Dynamic Pointing Decoder to recover from local maximum corresponding to initial incorrect guess in the Output layer and smarter span selection at test time. (<span style="color:FireBrick;">Best Dev Score F1: 0.75711 EM: 0.6574</span>)

  
Skills
======
* C/C++, Python, Java, MySQL, R, Matlab, Shell Script, Lisp
* PyTorch, Tensorflow

<!-- 

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
