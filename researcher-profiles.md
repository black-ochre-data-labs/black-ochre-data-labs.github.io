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
  grid-template-columns: auto auto auto;
  grid-template-rows: 1fr;
  grid-gap: 10px;
  align-items: center;
  margin-left: 20rem;
  margin-right: 20rem
  }

</style>

<main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
</html>
