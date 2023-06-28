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
  width: 800px;
  grid-template-columns: repeat(4, 300px);
  grid-auto-rows: minmax(300px, auto);
  align-content: top;
  align-items: top;
  justify-self: center;
  grid-gap: 3px;
  text-align: center;
  max-width: 50%;
 }


</style>
<body>
<main class="grid">
 {% include list-circles.html items=site.data.people.general %}
 </main>
 <br><h2><center>Genome Biology</center></h2><br>
 <main class="grid">
{% include list-circles.html items=site.data.people.genome_biology %}
  </main>
 <br><h2><center>Bioinformatics</center></h2><br>
 <main class="grid">
{% include list-circles.html items=site.data.people.bioinformatics %}
  </main>
 <br><h2><center>Cancer</center></h2><br>
 <main class="grid">
  {% include list-circles.html items=site.data.people.cancer %}
  </main>
 <br><h2><center>National Indigenous Genomics Network</center></h2><br>
 <main class="grid">
 {% include list-circles.html items=site.data.people.nigc %}
  </main>
</body>
</html>

