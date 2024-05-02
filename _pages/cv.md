---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

I am a computer science Ph.D. candidate at Aalborg University and I my research is in semantic data lakes, where I work on enabling semantic-aware data lake search by utilizing knowledge graphs and example-driven querying, scalable Big data management, entity linking, and (progressive) data lake indexing.

Work experience
======
* June, 2024 - September 2024: *Hasso Plattner Institute*, Research visitor
* September, 2021 - August, 2025 (expected): *Aalborg University* - PhD candidate on semantic data lakes
* November, 2020 - August, 2021: *Aalborg University* - Research Assistant on RDF graph database query optimization
* April, 2015 - October, 2020: *Nykilde Aps* - Software developer

Education
======
* Ph.D in Computer Science, Aalborg University, 2025 (expected)
* M.S. in Software, Aalborg University University, 2023
* B.S. in Software, Aalborg University, 2020
  
Skills
======
* C/C++, Python, and Java programming and SQL, SPARQL, and Cypher database querying
* Relational and graph databases
* Large-scale system architectures
* Information retrieval
* Semantic Web
* Linux
* Docker

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!--Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>-->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!--Service and leadership
======
* Currently signed in to 43 different slack teams-->

Public Contributions
======
* Merged pull request for the Microsoft's ALEX repository to add portability to large code bases.