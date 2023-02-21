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
 <main class="grid">
{% include list-circles.html items=site.data.people.genome_biology %}
  </main>
 <main class="grid">
{% include list-circles.html items=site.data.people.bioinformatics %}
  </main>
 <main class="grid">
{% include list-circles.html items=site.data.people.cancer %}
  </main>
 <main class="grid">
{% include list-circles.html items=site.data.people.nigc %}
  </main>
 <main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
 </body>
</html>
