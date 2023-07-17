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
  <div class="grid-item">
{% include list-circles.html items=site.data.people.genome_biology %} 
  </div>
  </div>
 <br><h2><center>Bioinformatics</center></h2><br>
 <div class="grid">
  <div class="grid-item">
{% include list-circles.html items=site.data.people.bioinformatics %}
  </div>
  </div>
 <br><h2><center>Cancer</center></h2><br>
 <div class="grid">
  <div class="grid-item">
  {% include list-circles.html items=site.data.people.cancer %}
  </div>
  </div>
 <br><h2><center>National Indigenous Genomics Network</center></h2><br>
 <div class="grid">
  <div class="grid-item">
 {% include list-circles.html items=site.data.people.nigc %}
  </div>
  </div>
</body>
</html>


# Testing removal of html
 {% include list-circles.html items=site.data.people.general %}

 ## Genome Biology md
 {% include list-circles.html items=site.data.people.genome_biology %} 

 <br><h2><center>Genome Biology html</center></h2><br>
 {% include list-circles.html items=site.data.people.genome_biology %} 

 ## Bioinformatics
 {% include list-circles.html items=site.data.people.bioinformatics %}

 ## Cancer
 {% include list-circles.html items=site.data.people.cancer %}

 ## National Indigenous Genomics Network
 {% include list-circles.html items=site.data.people.nigc %}
