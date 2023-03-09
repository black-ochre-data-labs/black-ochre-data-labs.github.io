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
  justify-content: space-around;
 }

</style>
<body>
<main class="grid">
{% include list-circles.html items=site.data.people.general %}
 </main>
 <h2><center>Genome Biology</center></h2>
 <main class="grid">
{% include list-circles.html items=site.data.people.genome_biology %}
  </main>
 <h2><center>Bioinformatics</center></h2>
 <main class="grid">
{% include list-circles.html items=site.data.people.bioinformatics %}
  </main>
 <h2><center>Cancer</center></h2>
 <main class="grid">
{% include list-circles.html items=site.data.people.cancer %}
  </main>
 <h2><center>National Indigenous Genomics Network</center></h2>
 <main class="grid">
{% include list-circles.html items=site.data.people.nigc %}
  </main>
 <main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
 </body>
</html>
