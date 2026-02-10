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
* Ph.D in Dynamical Systems, Jilin University, 2017.09-2022.06
* B.S. in Mathematics, Henan Normal University, 2013.09-2017.06

Work experience
======
* 2022.07-Present: Lecturer
  * Beijing Jiaotong University

* 2022.07-2024.07: Postdoc
  * Beijing Jiaotong  University
  

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
  
