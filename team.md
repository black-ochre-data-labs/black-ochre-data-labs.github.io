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

  <div class="h1c">
  Bioinformatics
</div>

{% include list-circles.html items=site.data.people.bioinformatics %}

  <div class="h1c">
  Cancer
</div>

{% include list-circles.html items=site.data.people.cancer %}

  <div class="h1c">
  National Indigenous Genomics Network
</div>

{% include list-circles.html items=site.data.people.nigc %}
  </body>
</html>
