---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
---
<html>
<style>

 .grid { 
  display: grid;
  grid-template-columns: auto auto auto;
  grid-template-rows: auto auto auto;
  grid-gap: 10px;
  align-items: center
  }

</style>

<main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
</html>
