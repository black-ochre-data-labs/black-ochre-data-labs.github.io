---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
layout: team
---

<html>
  <body>
{% include list-circles.html items=site.data.people.general %}
  <h1 class="center">Genome Biology</h1>
{% include list-circles.html items=site.data.people.genome_biology %} 
  <h1 class="center">Bioinformatics</h1>
{% include list-circles.html items=site.data.people.bioinformatics %}
  <h1 class="center">Cancer</h1>
{% include list-circles.html items=site.data.people.cancer %}
  <h1 class="center">National Indigenous Genomics Network</h1>
{% include list-circles.html items=site.data.people.nigc %}
  </body>
</html>
