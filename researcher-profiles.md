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
  grid-template-columns: 300px 300px 300px 300px;
  grid-auto-rows: 300px;
  grid-gap: 10px;
  align-items: center;
  margin-left: 4rem;
  margin-right: 4rem;
  word-break: normal
  }

</style>

<main class="grid">
{% include list-circles.html items=site.data.people.members %}
</main>
</html>
