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
  align-content: space-evenly;
  justify-items: center;
 }

</style>
<body>
<main class="grid">
{% include list-circles.html items=site.data.people.general %}
 </main>
 <h2>Genome Biology</h2>
 <main class="grid">
{% include list-circles.html items=site.data.people.genome_biology %}
  </main>
 <h2>Bioinformatics</h2>
 <main class="grid">
{% include list-circles.html items=site.data.people.bioinformatics %}
  </main>
 <h2>Cancer</h2>
 <main class="grid">
{% include list-circles.html items=site.data.people.cancer %}
  </main>
 <h2>National Indigenous Genomics Network</h2>
 <main class="grid">
{% include list-circles.html items=site.data.people.nigc %}
  </main>
 <main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
 </body>
</html>
