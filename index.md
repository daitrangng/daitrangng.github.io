---
layout: base
css:
  - '/css/reading.css'
  - '/css/activity.css'
  - '/css/post-list.css'
---

{% include header.html type="page" %}

<!-- intro -->
<section class="alt-color me-desc">
  {% include sections/sec-front-md.html %}
  <div class="me-description">
  My full name is "Thi Dai Trang Nguyen", I am a Tenure-track Assistant Professor in the Department of Mathematics and Statistics at South Dakota State University.
  </div>
  <div class="me-description">
    Research interest:
    <ul>
      <li>Optimization, Optimal Control and Applications, Nonlinear and Variational Analysis</li>
      <li> AI & Machine Learning, Statistics </li>
    </ul>
  </div>
  {% include sections/sec-back.html %}
</section>

<section class="announcement">
  <div class="container" markdown="1">
  **I am seeking motivated graduate students (Master’s and Ph.D.)** to join my research group at South Dakota State University (SDSU). Research focuses on optimization, optimal control and machine learning.  Teaching Assistant (TA) positions are available, and fully-funded. Please email a brief CV and statement of interest to [trang.nguyen@sdstate.edu](mailto:trang.nguyen@sdstate.edu). Due to the high volume of applications, I might not be able to reply to all; If your interests closely align with my research areas, you will receive an email to schedule a meeting or potential next steps.
  </div>
</section>

<!-- education -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-timeline.html
    heading="Experience"
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
  {% include sections/sec-activity.html
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
    heading="Talks"
    source=site.data.conferences
    ref="conferences"
  %}
  {% include sections/sec-back.html %}
</section>

<!-- Media Coverage -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-activity.html
    heading="Media Coverage"
    source=site.data.media
    ref="media"
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
<section class="alt-color not-pb-0">
  {% include sections/sec-front-md.html %}
  {% include sections/sec-contact.html %}
  {% include sections/sec-back.html %}
</section>
