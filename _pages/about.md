---
permalink: /
title: "À propos"
excerpt: "À propos"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Étudiant à la maîtrise en informatique à l'Université de Montréal sous la supervision de [Pierre Poulin](http://www.iro.umontreal.ca/~poulin/). Mon mémoire a été accepté par le jury et une version finale est déposée. Je détiens aussi un baccalauréat en informatique de l'Université de Montréal.

Publication
======

Semi-Transparent Textures Based on Opaque and Transparent Texels Augmented with a Thickness
------
Le rendu en temps réel repose sur des compromis entre la performance et le réalisme. Un de ces compromis est de représenter des matériaux plus minces tels que les tissus comme étant infiniment minces pour économiser mémoire et temps de rendu. Par contre, cette perte de dimension prive la surface de propriétés essentielles à certains effets visuels. Dans ce mémoire, nous présentons une méthode pour simuler les effets de l’épaisseur sur des surfaces semi-transparentes en utilisant des textures composées de texels opaques et transparents. Nous analysons les trous formés par les texels transparents et nous conservons de l’information sur les contours des trous dans une structure hiérarchique compatible avec la méthode de filtrage de textures par MIP map. Nous dérivons des équations représentant la proportion de lumière passant dans un trou avec des murs intérieurs en fonction de l’angle incident des rayons de lumière. Nous combinons ces équations avec l’information conservée pour calculer un terme de transparence à différents niveaux de détail en temps réel.

![Thesis Figure](images/figure_4_3.PNG)
