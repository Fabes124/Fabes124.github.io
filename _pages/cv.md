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
  * Passed all three qualifying exams, 2026
  * Master's thesis in progress on syntomic cohomology
* B.A. in Mathematics and Physics (double major), Johns Hopkins University, 2025
  * General honors; departmental honors in physics

Research interests
======
Arithmetic geometry in mixed characteristic (curves and their Jacobians, class groups, Iwasawa theory); $p$-adic Hodge theory (syntomic and prismatic cohomology); homotopy theory (spectral algebraic geometry, topological Hochschild and cyclic homology); automorphic forms.

Honors and awards
======
* Graduate fellowship, Louisiana State University, 2025&ndash;present
* Undergraduate teaching award, Department of Mathematics, Johns Hopkins University, 2025
* General honors and departmental honors in physics, Johns Hopkins University, 2025
* Dean's List, Johns Hopkins University, Spring 2024 and Fall 2024

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
* **Frobenius algebra sheaves and genus-2 curves**, Louisiana State University, 2025&ndash;present
  * With Jerome Hoffman, Fang-Ting Tu, and Scott Baldridge
  * Self-dual Frobenius algebra sheaves on curves and rings of integers and their behavior in $\mathbb{Z}_2$-extensions; explicit genus-2 curves with split Jacobians.
* **Topological quantum field theories over algebraic field extensions**, Johns Hopkins University, 2024&ndash;2025
  * Mentors: Mikhail Khovanov and Mee Seong Im
  * Frobenius algebra structures over Dedekind domains via projective modules; led to the published paper listed above.
* **Drinfeld centers of fusion 2-categories**, Johns Hopkins University, 2024
  * Mentor: Thomas Waddleton (Ibou Bah's group)
  * Computed Drinfeld centers of fusion 2-categories and studied their Morita equivalence classes.
* **Von Neumann algebras in mathematical physics**, Johns Hopkins University, 2023
  * Mentor: Ibou Bah
  * Classification of factors and algebras of observables, with de Sitter space as a case study.
* **X-ray contribution of black holes in the Milky Way**, Johns Hopkins University, 2023
  * Mentor: Marc Kamionkowski
  * Estimated X-ray emission from Galactic black holes and its detectability by eROSITA.

Graduate coursework
======
* **Louisiana State University:** Algebra I; Real Analysis I; Topology I; Algebraic Topology; seminars in algebra and number theory, geometry and topology, and functional analysis
* **Johns Hopkins University:** Algebra I&ndash;II; Algebraic Topology I&ndash;II; Complex Variables; Riemann Surfaces; Number Theory I; Algebraic Geometry I&ndash;II; Lie Groups and Lie Algebras; Riemannian Geometry II. Physics: Quantum Field Theory I&ndash;II; General Relativity; Advanced Particle Theory

Reading courses
======
* **Louisiana State University:** deformation theory and formal moduli problems (Lurie, Pridham); class field theory; supersymmetry and Morse theory (Fall 2026). Scheme theory and sheaf cohomology; algebraic number theory (number fields); fusion 2-categories (2025&ndash;2026)
* **Johns Hopkins University:** algebraic geometry (varieties, schemes, and algebraic surfaces), with Vyacheslav Shokurov; geometric invariant theory, with Mee Seong Im
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

Service, mentoring, and leadership
======
* Founder and Director, Physics Undergraduate Reading Program, JHU Society of Physics Students, 2023&ndash;2025
  * Modeled on the math Directed Reading Program, for first- and second-year students preparing for research
  * Led reading courses in tensor calculus, differential topology, category theory, symmetry in particle physics, string theory, and continuum mechanics
* Mentor and mentee, JHU physics department mentorship program; organized review sessions for Advanced Classical Mechanics and Quantum Mechanics
* Academic mentor to about thirty undergraduates in mathematics and physics (course planning, research interests, finding advisors), 2023&ndash;2025
* Vice-President, JHU Math Club, 2023&ndash;2025
* Treasurer, JHU Society of Physics Students, 2022&ndash;2023 (named a Distinguished Chapter)

Skills
======
* Python, Mathematica, MATLAB
