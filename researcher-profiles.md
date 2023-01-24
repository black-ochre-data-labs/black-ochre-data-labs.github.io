---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
full-width: true
---
<html>
<style>

 .grid { 
  display: inline-grid;
  grid-template-columns: repeat(4, 300px);
  grid-auto-rows: minmax(200px, auto);
  gap: 10px;
  align-items: start;
  justify-items: center;
  margin-top: 1rem;
  margin-left: 4rem;
  margin-right: 4rem;
  word-break: normal
  }

</style>

<main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
</html>
