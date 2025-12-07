---
layout: archive
title: "CV"
permalink: /cv_fr/
author_profile: false
redirect_from:
  - /resume_en
---

{% include base_path %}

<link rel="stylesheet" href="{{ base_path }}/assets/css/cv-style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

<style>
  .archive {
    width: 80%;
    margin: 0 auto;
    float: none;
    padding-right: 0;
  }
  
  @media (min-width: 80em) {
    .archive {
      width: 70%;
    }
  }
</style>

<div class="cv-header-nav">
<p>
CV en français (disponible aussi en 
<a href="https://juitinglu.github.io/cv_en/">English</a> 
et en 
<a ref="https://juitinglu.github.io/cv_zh/">中文</a>).
</p>
</div>

<!-- {% assign cv = site.data.cv %} -->
{% include cv-template.html cv=site.data.cv_fr %}
<!-- {% include cv-template.html lang="FR" %} -->

<!-- <div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div> -->
