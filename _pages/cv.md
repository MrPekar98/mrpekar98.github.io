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
* Ph.D in Computer Science, Aalborg University, 2025 (expected)
* M.S. in Software, Aalborg University University, 2023
* B.S. in Software, Aalborg University, 2020

Work experience
======
* 2015 - 2020: Software developer
  * Nykilde Aps
  * Data management

* 2020 - 2021: Research Assistant
  * Aalborg University
  * RDF graph database query optimization research
  
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
* Merged pull request for the Microsoft ALEX repository to add portability to large code bases.