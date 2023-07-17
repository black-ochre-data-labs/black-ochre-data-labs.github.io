---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
full-width: false
---
<html>
<style>
 .grid { 
  display: grid;
  grid-template-columns: 300px 300px 300px;
  grid-gap: 5px;
  flex-wrap: wrap;
  align-items: start;
  justify-content: center;
 }
</style>
 
<body>
<div class="grid">
 {% include list-circles.html items=site.data.people.general %}
</div>
 <br><h2><center>Genome Biology</center></h2><br>
 <div class="grid">
{% include list-circles.html items=site.data.people.genome_biology %} 
 </div>
 <br><h2><center>Bioinformatics</center></h2><br>
 <div class="grid">
{% include list-circles.html items=site.data.people.bioinformatics %}
 </div>
 <br><h2><center>Cancer</center></h2><br>
 <div class="grid">
  {% include list-circles.html items=site.data.people.cancer %}
 </div>
 <br><h2><center>National Indigenous Genomics Network</center></h2><br>
 <div class="grid">
 {% include list-circles.html items=site.data.people.nigc %}
 </div>
</body>
</html>
