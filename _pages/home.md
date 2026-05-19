---
title: ""
layout: singlepage
sitemap: false
permalink: /
---

{% include profile_header.html %}

<section id="news" class="section-after-header">
<h2>News</h2>
<ul class="news-list">
  {% for item in site.data.news %}
  <li><strong>{{ item.date }}</strong> — {{ item.headline }}</li>
  {% endfor %}
</ul>
</section>

<section id="research-interests">
<h2>Research Interests</h2>
<p>
I am interested in improving the reliability and security of AI systems, with a current focus on diffusion models.
</p>
</section>

<section id="papers">
<h2>Papers</h2>
{% include research_content.html %}
</section>

<section id="experience">
<h2>Experience</h2>
<ul class="experience-list">
  <li>
    <strong>Graduate Student Researcher</strong><br/>
    <span class="exp-org">The University of Texas at Austin</span><br/>
    <span class="exp-dates">May 2026 – Present</span><br/>
    <span class="exp-super">Supervisor: Professor Sanjay Shakkottai</span>
  </li>
  <li>
    <strong>Undergraduate Student Researcher</strong><br/>
    <span class="exp-org">University of Illinois Urbana-Champaign (Information &amp; Intelligence Group)</span><br/>
    <span class="exp-dates">June 2024 – May 2026</span><br/>
    <span class="exp-super">Supervisors: Professors Lav Varshney &amp; Daniel Alabi</span>
  </li>
  <li>
    <strong>Research Intern (Tactical Satellite Communications)</strong><br/>
    <span class="exp-org">MIT Lincoln Laboratory (Group 64), Lexington, MA</span><br/>
    <span class="exp-dates">May 2025 – August 2025</span><br/>
    <span class="exp-super">Supervisor: Dwight Hutchenson</span>
  </li>
  <li>
    <strong>Quantitative Research Intern</strong><br/>
    <span class="exp-org">Nebula Research and Development, New York, NY</span><br/>
    <span class="exp-dates">October 2023 – August 2024</span><br/>
    <span class="exp-super">Supervisor: Dr. Limin Wang</span>
  </li>
  <li>
    <strong>Undergraduate Researcher</strong><br/>
    <span class="exp-org">The Wharton School, Philadelphia, PA</span><br/>
    <span class="exp-dates">August 2022 – May 2024</span><br/>
    <span class="exp-super">Supervisor: Professor Prasanna Tambe</span>
  </li>
</ul>
</section>
