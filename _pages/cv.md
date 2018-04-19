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
* MSc in Mathematics, Imperial College London, 2009
* MSc in Financial Mathematics, CASS Business School, 2013
* Ph.D in Statisics, University of Warwick, 2018 (expected)

Work experience
======
* 2014 - 2015: Statistician, Warwick Analytics
* 2012 - 2014: Assistant Vice President Developer, Barclays Capital
* 2009 - 2012: Analyst Developer, Royal Bank of Scotland


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
