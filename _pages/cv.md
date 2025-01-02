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
* Ph.D in Bioinformatics, Georgia Institute of Technology, 2026 (expected)
* M.S. in Bioinformatics & Computational Biology, Worcester Polytechnic Institute, 2021
* B.S. in Pharmacy, Beijing University of Chinese Medicine, 2019

You can view my CV in here

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
  

