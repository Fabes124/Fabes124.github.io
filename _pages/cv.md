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
* Ph.D. in Mathematics, Louisiana State University, 2025&ndash;present
  * Working with Jerome Hoffman, Fang-Ting Tu, and Scott Baldridge
* B.A. in Mathematics, Johns Hopkins University, 2025
* B.S. in Physics, Johns Hopkins University, 2025

Research interests
======
Arithmetic geometry (curves, Jacobians and Prym varieties; Iwasawa theory; $p$-adic Hodge theory and syntomic cohomology); algebraic geometry (moduli, deformation theory, formal moduli problems); the Langlands program (automorphic forms and duality, as tools for arithmetic geometry); homotopy theory (motivic and chromatic homotopy theory, higher algebra); mathematical physics (topological quantum field theories; electric–magnetic duality and geometric Langlands).

{% for category in site.publication_category %}
{% assign items = site.publications | where: "category", category[0] | sort: "order", "last" %}
{% if items.size > 0 %}
<h1>{{ category[1].title }}</h1>
<ul>{% for post in items %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
{% endif %}
{% endfor %}

Research experience
======
* **Topological quantum field theories over algebraic field extensions**, Johns Hopkins University, 2024&ndash;2025
  * Mentors: Mikhail Khovanov and Mee Seong Im
  * Frobenius algebra structures over Dedekind domains via projective modules; led to the paper listed above.
* **Drinfeld centers of fusion 2-categories**, Johns Hopkins University, 2024
  * Mentor: Thomas Waddleton (Ibou Bah's group)
  * Computed Drinfeld centers of fusion 2-categories and studied their Morita equivalence classes.
* **Von Neumann algebras in mathematical physics**, Johns Hopkins University, 2023
  * Mentor: Ibou Bah
  * Classification of factors and algebras of observables, with de Sitter space as a case study.
* **X-ray contribution of black holes in the Milky Way**, Johns Hopkins University, 2023
  * Mentor: Marc Kamionkowski
  * Estimated X-ray emission from Galactic black holes and its detectability by eROSITA.

Directed reading
======
* Characteristic classes (Milnor&ndash;Stasheff), JHU Math Directed Reading Program, Spring 2023, with Akira Tominaga
* Differential geometry and topology (Nakahara), JHU Math Directed Reading Program, Fall 2022, with Milton Lin

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

* Tutor, GoPeer, 2021&ndash;2022: AP and college calculus and physics

Service and leadership
======
* Vice-President, JHU Math Club, 2023&ndash;2025
* Reading Program Director, JHU Society of Physics Students, 2023&ndash;2025
  * Founded the Physics Undergraduate Reading Program in 2023, modeled on the math Directed Reading Program
  * Led reading courses on differential topology, category theory, string theory, and symmetry in theoretical physics
* Treasurer, JHU Society of Physics Students, 2022&ndash;2023 (named a Distinguished Chapter)

Skills
======
* Python, Mathematica, MATLAB
