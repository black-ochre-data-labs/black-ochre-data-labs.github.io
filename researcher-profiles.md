---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
---

<html>
  <head>

<style>

 .grid { 
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 30px;
  align-items: center;
  justify-items: center;
  }
.grid img {
  border: 1px solid #ccc;
  box-shadow: 2px 2px 6px 0px  rgba(0,0,0,0.3);
  max-width: 100%;
}
</style>

<main class="grid">
{% include list-circles.html items=site.data.people.members %}
  
 </div>
    </div>
  </main>
