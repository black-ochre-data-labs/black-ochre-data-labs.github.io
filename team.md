---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
layout: team
---

<html>
  <body>
  
{% include list-circles.html items=site.data.people.general %}

  <div text-align="center">
  <h1>Genome Biology</h1>
</div>

{% include list-circles.html items=site.data.people.genome_biology %} 

  <div text-align="center">
  <h1>Bioinformatics</h1>
</div>

{% include list-circles.html items=site.data.people.bioinformatics %}

  <div text-align="center">
  <h1>Cancer</h1>
</div>

{% include list-circles.html items=site.data.people.cancer %}

  <div text-align="center">
  <h1>National Indigenous Genomics Network</h1>
</div>

{% include list-circles.html items=site.data.people.nigc %}
  </body>
</html>
