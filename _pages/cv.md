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
* Pursuing Ph.D from School of Artificial Intelligence, Indian Institute of Technology Delhi
* B.Tech in Electrical Engineering from National Institute of Technology Kurukshetra

Work experience
======
* Spring 2020-Present: Administrative Assistant
  * Indian Institute of Technology Delhi
  * Duties includes: Clerical, website maintenance, procurement
  * Supervisor: Head, CARE
  
Skills
======
* HTML, CSS
* Python
* Machine Learning
  * CNN
  * RNN
  * Transformers
  * GAN
* Generative AI
* Leetcode rank:
* LLMs

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

