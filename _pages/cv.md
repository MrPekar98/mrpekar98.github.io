---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

I am a computer science Ph.D. candidate at Aalborg University and my research is in semantic data lakes, where I work on enabling semantic-aware data lake search by utilizing knowledge graphs and example-driven querying, scalable Big data management, entity linking, and (progressive) data lake indexing.

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

Education
======
* Ph.D in Computer Science, Aalborg University, 2025 (expected)
* M.S. in Software, Aalborg University University, 2023
* B.S. in Software, Aalborg University, 2020

Positions
======
* June, 2024 - September 2024: __Hasso Plattner Institute__, Research visitor
* September, 2021 - August, 2025 (expected): __Aalborg University__ - PhD candidate on semantic data lakes
* November, 2020 - August, 2021: __Aalborg University__ - Research Assistant on RDF graph database query optimization
* April, 2015 - October, 2020: __Nykilde Aps__ - Software developer
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* C/C++, Python, Bash, and Java programming and SQL, SPARQL, and Cypher querying
* Relational and graph databases
* Large-scale system architectures
* Big Data management
* Data integration
* Information retrieval
* Semantic Web
* Linux
* Docker
  
<!--Service and leadership
======
* Currently signed in to 43 different slack teams-->

<!--Public Contributions
======
* Merged pull request for the Microsoft's ALEX repository to add portability to large code bases.-->
