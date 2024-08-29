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
 
* **Sept.2018-Dec.2021** Ph.D. in Physics supervised by Hugues Chaté, [SPEC](https://iramis.cea.fr/spec/), CEA Saclay, Gif-sur-Yvette, France.
* &emsp;&emsp;**2017**&emsp;&emsp; [Master in Physics of Complex Systems](https://physics-complex-systems.fr/), [ENS Paris-Saclay](https://ens-paris-saclay.fr/).
* &emsp;**2015-2016**&nbsp; Prepare a competitive teacher recruitment exam in Physics, ENS Cachan, Cachan, France.
* &emsp;&emsp;**2014**&emsp;&emsp;  Bachelor degree in Physics, Université Paris-Sud, Orsay, France.



  
Research experience
======

* **May.2022-Aug.2025**: Postdoc
  * [LIPhy](https://liphy.univ-grenoble-alpes.fr/en), UGA, Grenoble, France
  * Advisor: [Philippe Peyla](http://liphy-annuaire.univ-grenoble-alpes.fr/pages_personnelles/philippe_peyla/)
* **Sept.2018-Dec.2021**: Ph.D.
  * [SPEC](https://iramis.cea.fr/spec/), CEA Saclay, Gif-sur-Yvette, France
  * Supervisor: Hugues Chaté
* **Sept.2017-Jul.2018**: Research internship
  * [Physics of Complex Systems and stat. mech.](https://complex.ulb.ac.be/), ULB, Bruxelles,Belgium.
  * Supervisor: [Pierre Gaspard](https://gaspard.pierre.web.ulb.be/)
* **Mar.2017-Jun.2017**: Research internship
  * [Gulliver](https://www.gulliver.espci.fr/?-home-), ESPCI, Paris, France
  * Supervisor: [Ken Sekimoto](https://www.pct.espci.fr/~sekimoto/sekimoto_hp_espci.html)
* **Apr.2015-Jul.2015**: Research internship
  * [Alfvén Lab.](http://www.alfvenlab.kth.se/), KTH, Stockholm, Sweden
  * Supervisor: [Jon Tomas Gudmundsson](http://langmuir.raunvis.hi.is/~tumi/eindex.html)
  
Teaching experience
======
<!-- Remettre comme il faut -->
* **Sept.2024-Jul.2025**: Teaching assistant
  * [Université Grenoble Alpes](https://www.univ-grenoble-alpes.fr/), Grenoble, France
  * Mechanics, tutorials and laboratory courses for 100 hours (undergraduate students).
  * Lab work on Signal processing, 18 hours (graduate students)
* **Sept.2018-Jul.2021**: Teaching assistant
  * [Université Paris-Saclay](https://www.universite-paris-saclay.fr/), Orsay, France
  * Geometrical optics, lectures, tutorials and laboratory courses for 153 hours (undergraduate students).
  * Lab work in Mechanics, 30 hours (undergraduate students).


Publications
======
<ol reversed>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ol>

Oral presentations
======

## Invited talks

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

## Contributed talks

## Seminars

## Posters
<ul>
    {% assign talks = site.talks | where:'type', 'Invited talk' %}
    {% for post in talks reversed %}
      {% include my-archive-single-talk.html %}
    {% endfor %}
</ul>
 
<ul>
    {% assign talks = site.talks | where:'type', 'Contributed talk' %}
    {% for post in talks reversed %}
      {% include my-archive-single-talk.html %}
    {% endfor %}
</ul>
 
<ul>
    {% assign talks = site.talks | where:'type', 'Seminar' %}
    {% for post in talks reversed %}
      {% include my-archive-single-talk.html %}
    {% endfor %}
</ul>
 
<ul>
    {% assign talks = site.talks | where:'type', 'Poster' %}
    {% for post in talks reversed %}
      {% include my-archive-single-talk.html %}
    {% endfor %}
</ul>

<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
   -->