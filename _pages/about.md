---
layout: academic
permalink: /
title: "About"
redirect_from:
  - /about/
  - /about.html
---

<header class="profile-header">
  <img class="profile-photo" src="{{ '/images/profile-2026.png' | relative_url }}" alt="Nannan Zhang" width="180" height="180">
  <div>
    <h1>Nannan Zhang</h1>
    <p class="profile-role">Ph.D. student in Artificial Intelligence</p>
    <p class="profile-affiliation">Institute of Artificial Intelligence, Xiamen University</p>
    <p class="profile-location">Xiamen, Fujian, China</p>
    <div class="profile-contact">
      <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
      <a href="https://github.com/{{ site.author.github }}">GitHub ↗</a>
    </div>
  </div>
</header>

<div class="intro" markdown="1">
I am a Ph.D. student in Artificial Intelligence at the Institute of Artificial Intelligence, **Xiamen University**, supervised by Prof. [Bin Ren](https://bren.xmu.edu.cn).

I completed my master's studies in Materials Engineering at the College of Chemistry and Chemical Engineering, Xiamen University (2023–2026), also under the supervision of Prof. Bin Ren. I received my bachelor's degree in Applied Chemistry from Nanjing Tech University in 2023.
</div>

<section class="section" aria-labelledby="research">
  <h2 id="research">Research interests</h2>
  {% include research-interests.html %}
</section>
<section class="section" aria-labelledby="news">
  <h2 id="news">Recent news</h2>
  <div class="news-item"><p>Update and maintain <a href="https://ramancloud.xmu.edu.cn">Ramancloud</a>, focusing on spectral denoising and background correction algorithms.</p></div>
</section>
<section class="section" aria-labelledby="publications">
  <h2 id="publications">Publications</h2>
  <div class="empty-state"><p>Coming soon.</p></div>
</section>
<section class="section" aria-labelledby="cv">
  <h2 id="cv">CV</h2>
  {% include education.html %}
</section>
