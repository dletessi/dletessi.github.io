---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Current position

**Maître de conférences in fluid mechanics** — Université Claude Bernard Lyon 1; Laboratoire de Mécanique des Fluides et d'Acoustique (LMFA), Turbulence and Stability group.

# Previous research positions

- **2025** — Postdoctoral researcher, Institut de Recherche sur les Phénomènes Hors Équilibre (IRPHE), Marseille.
- **2024** — Postdoctoral researcher, Institut de Mécanique des Fluides de Toulouse (IMFT), Toulouse.

# Education

- **2024** — PhD in Fluid Mechanics, Université de Toulouse / IMFT. Thesis: *Chute en régime inertiel de cylindres isolés ou en groupes dans une cellule mince*.
- **2020** — Master's degree in Fluid Dynamics and Energy, Université Paris-Saclay.
- **2020** — Magistère in Fundamental Physics, Université Paris-Saclay.
- **2017** — Preparatory classes (Mathematics–Physics), Lycée Georges Clemenceau, Nantes.

# Research profile

Turbulence and hydrodynamic instabilities; fluid-structure interactions; multiphase and particle-laden flows; experimental fluid mechanics.

# Teaching

**96 contact hours** at Université Toulouse III – Paul Sabatier (2020–2023), including mechanics, thermal sciences, and scientific computing with Python.

# Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

# Talks

{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
