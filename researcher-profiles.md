---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
full-width: true
---
<html>
<style>

 .grid { 
  display: grid;
  grid-template-columns: repeat(4, 300px);
  grid-auto-rows: minmax(300px, auto);
  max-width: 1200px;
  margin: auto;
  gap: 10px;
  word-break: normal;
 }

</style>
<body>
<main class="grid">
<center>
 {% include list-circles.html items=site.data.people.general %}
 </center>
 </main>
 <br><h2><center>Genome Biology</center></h2><br>
 <main class="grid">
  <center>
{% include list-circles.html items=site.data.people.genome_biology %}
   </center>
  </main>
 <br><h2><center>Bioinformatics</center></h2><br>
 <main class="grid">
  <center>
{% include list-circles.html items=site.data.people.bioinformatics %}
   </center>
  </main>
 <br><h2><center>Cancer</center></h2><br>
 <main class="grid">
 <center>
  {% include list-circles.html items=site.data.people.cancer %}
  </center>
  </main>
 <br><h2><center>National Indigenous Genomics Network</center></h2><br>
 <main class="grid">
<center>
 {% include list-circles.html items=site.data.people.nigc %}
 </center>
  </main>
 </body>
</html>
