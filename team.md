---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
layout: team
---

<html>
  <body>
  
{% include list-circles.html items=site.data.people.general %}

<h1c>Genome Biology</h1c>

{% include list-circles.html items=site.data.people.genome_biology %} 

  <div text-align="center">
  <h1c>Bioinformatics</h1c>
</div>

{% include list-circles.html items=site.data.people.bioinformatics %}

  <div text-align="center">
  <h1c>Cancer</h1c>
</div>

{% include list-circles.html items=site.data.people.cancer %}

  <div text-align="center">
  <h1c>National Indigenous Genomics Network</h1c>
</div>

{% include list-circles.html items=site.data.people.nigc %}
  </body>
</html>
