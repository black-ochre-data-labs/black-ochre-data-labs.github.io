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
  grid-auto-rows: minmax(200px, auto);
  max-width: 960px;
  gap: 10px;
  margin: auto;
  word-break: normal;
  align-content: space-evenly
 }

</style>
<body>
<main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
 </body>
</html>
