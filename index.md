---
layout: base
css:
  - '/css/reading.css'
  - '/css/activity.css'
  - '/css/post-list.css'
---

{% include header.html type="page" %}

<!-- intro -->
<section class="alt-color">
  {% include sections/sec-front-md.html %}
  <div class="me-description">
  My full name is "Thi Dai Trang Nguyen", I am currently a Ph.D. Candidate and Graduate Teaching Assistant in Mathematics at Wayne State University.
  </div>
  <div class="me-description">
    Research interest:
    <ul>
      <li>Optimization, Optimal Control, Nonlinear and Variational Analysis</li>
      <li>ODEs/PDEs, Statistics, Data Science, Dynamical Systems and Applications</li>
    </ul>
  </div>
  {% include sections/sec-back.html %}
</section>

<!-- education -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-timeline.html
    heading="Education"
    source=site.data.education
  %}
  {% include sections/sec-back.html %}
</section>

<!-- publications -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-publications.html
    heading="Publications"
    source=site.data.publications
    ref="publications"
  %}
  {% include sections/sec-back.html %}
</section>

<!-- services / activities -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-publications.html
    heading="Services / Extracurricular Activies"
    source=site.data.activities
    ref="activities"
  %}
  {% include sections/sec-back.html %}
</section>

<!-- teaching -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-teaching.html
    heading="Teaching"
    source=site.data.teaching
    ref="teaching" %}
  {% include sections/sec-back.html %}
</section>

<!-- conferences -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-conferences.html
    heading="Conferences"
    source=site.data.conferences
    ref="conferences"
  %}
  {% include sections/sec-back.html %}
</section>

<!-- award -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-teaching.html
    heading="Honors and Awards"
    source=site.data.award
    light=true
    ref="award" %}
  {% include sections/sec-back.html %}
</section>

<!-- contact -->
<section class="alt-color">
  {% include sections/sec-front-md.html %}
  {% include sections/sec-contact.html %}
  {% include sections/sec-back.html %}
</section>
