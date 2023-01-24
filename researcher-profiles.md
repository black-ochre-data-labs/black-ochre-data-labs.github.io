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
  gap: 10px;
  align-items: start;
  margin-top: 1rem;
  margin-left: 8rem;
  margin-right: 8rem;
  word-break: normal;
  position: relative
  }

</style>

<main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
</html>
