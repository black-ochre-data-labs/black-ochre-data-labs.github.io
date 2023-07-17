---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
layout: team
---
<html>
<body>
<div class="grid">
 <div class="grid-item">
 {% include list-circles.html items=site.data.people.general %}
 </div>
</div>
 <br><h2><center>Genome Biology</center></h2><br>
 <div class="grid">
  <div class="grid-item" align="center">
{% include list-circles.html items=site.data.people.genome_biology %} 
  </div>
  </div>
 <br><h2><center>Bioinformatics</center></h2><br>
 <div class="grid">
  <div class="grid-item" align="center">
{% include list-circles.html items=site.data.people.bioinformatics %}
  </div>
  </div>
 <br><h2><center>Cancer</center></h2><br>
 <div class="grid">
  <div class="grid-item" align="center">
  {% include list-circles.html items=site.data.people.cancer %}
  </div>
  </div>
 <br><h2><center>National Indigenous Genomics Network</center></h2><br>
 <div class="grid">
  <div class="grid-item" align="center">
 {% include list-circles.html items=site.data.people.nigc %}
  </div>
  </div>
</body>
</html>
