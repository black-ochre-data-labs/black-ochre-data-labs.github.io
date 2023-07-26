---
title: People
subtitle: Meet the team at Black Ochre Data Labs
default_profile_img: /assets/img/default.png
layout: team
---

<html>
  <body>
{% include list-circles.html items=site.data.people.general %}
{% include list-circles.html items=site.data.people.bioinformatics %} 
{% include list-circles.html items=site.data.people.external %}
{% include list-circles.html items=site.data.people.students %}
  <h1 class="center">National Indigenous Genomics Network</h1>
{% include list-circles.html items=site.data.people.network %}
  </body>
</html>
