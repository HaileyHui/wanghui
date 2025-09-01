<style>
.page__title { display: none; }
</style>
---
permalink: /
title: "Hui Wang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- About Me 部分 -->
<section id="aboutme">
  <h2><i class="fas fa-user"></i> About Me</h2>
  {% include_relative aboutme.html %}
</section>

<!-- Publications 部分 -->
<section id="publications">
  <h2><i class="fas fa-book"></i> Publications</h2>
  {% include_relative publications.html %}
</section>

<!-- Educations 部分 -->
<section id="educations">
  <h2><i class="fas fa-graduation-cap"></i> Educations</h2>
  {% include_relative educations.html %}
</section>

<!-- Honors and Awards 部分 -->
<section id="honors-and-awards">
  <h2><i class="fas fa-trophy"></i> Honors and Awards</h2>
  {% include_relative honors.html %}
</section>
