---
permalink: /
title: "Hui Wang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* 隐藏首页的标题区块和多余空白 */
.page__header,
.page__title,
.page__lead,
.page__meta {
  display: none;
  margin: 0;
  padding: 0;
}
</style>

<!-- About Me 部分 -->
<section id="aboutme">
  <h2>👤 About Me</h2>
  {% include_relative aboutme.html %}
</section>

<!-- Publications 部分 -->
<section id="publications">
  <h2>📚 Publications</h2>
  {% include_relative publications.html %}
</section>

<!-- 新增：Projects 部分 -->
<section id="projects">
  <h2>🛠️ Projects</h2>
  {% include_relative projects.html %}
</section>

<!-- Educations 部分 -->
<section id="educations">
  <h2>🎓 Educations</h2>
  {% include_relative educations.html %}
</section>

<!-- Honors and Awards 部分 -->
<section id="honors">
  <h2>🏆 Honors and Awards</h2>
  {% include_relative honors.html %}
</section>
