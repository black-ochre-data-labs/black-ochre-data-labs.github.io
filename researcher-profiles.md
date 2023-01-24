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
  grid-template-columns: 200px 200px 200px 200px 200px 200px;
  grid-template-rows: auto;
  grid-gap: 10px;
  align-items: center;
  margin-left: 5rem;
  margin-right: 5rem;
  word-break: normal
  }

</style>

<main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
</html>
