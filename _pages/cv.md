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
* Dr. rer. nat. in Mathematics, RWTH Aachen University, 2024
* M. Sc. in Mathematics, RWTH Aachen University, 2018
* B. Sc. in Mathematics, RWTH Aachen University, 2016

Work experience
======
* 2023- now: Postdoc
  * Czech Academy of Sciences, Computer Science Institute
  * Project: Graph Limits and Beyond

* 2018-2022: Research Assistant
  * RWTH Aachen University, Lehrstuhl II für Mathematik

  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% comment %}  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
{% endcomment %}
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
For a long version of my cv, see [here](http://annamargarethelimbach.github.io/files/cv_limbach.pdf) (last updated December 2024).