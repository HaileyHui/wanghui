---
permalink: /
title: "HomePage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

<!-- About Me 部分 -->
<section id="aboutme">
  <h2><i class="fas fa-user"></i> About Me</h2>
  {% include_relative _pages/aboutme.html %}
</section>

<!-- Publications 部分 -->
<section id="publications">
  <h2><i class="fas fa-book"></i> Publications</h2>
  {% include_relative _pages/publications.html %}
</section>

<!-- Educations 部分 -->
<section id="educations">
  <h2><i class="fas fa-graduation-cap"></i> Educations</h2>
  {% include_relative _pages/educations.html %}
</section>

<!-- Honors and Awards 部分 -->
<section id="honors-and-awards">
  <h2><i class="fas fa-trophy"></i> Honors and Awards</h2>
  {% include_relative _pages/honors.html %}
</section>
