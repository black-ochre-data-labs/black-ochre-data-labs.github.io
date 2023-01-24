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
  gap: 10px;
  margin-top: 1rem;
  margin-left: 4rem;
  margin-right: 4rem;
  word-break: normal;
  justify-content: space-evenly;
  justify-items: center;
  align-content: space-evenly;
  align-items: center
 }

</style>

<main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
</html>
