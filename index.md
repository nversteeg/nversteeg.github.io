---
layout: default
# No `title:` here, so the layout prints no <h1> and the home page opens with the photo + bio.
---

<div class="intro">

  <!-- Toggling the photo = this filename, plus the preset block in style.css.
       No width/height attributes: the CSS sets width + aspect-ratio, which
       already reserves the box before the image loads. -->
  <img class="intro-photo"
       src="{{ '/assets/img/headshot-square.jpg' | relative_url }}"
       alt="Portrait of {{ site.title }}">

  <div class="intro-bio" markdown="1">

I am a PhD candidate in [Business and Public
Policy](https://haas.berkeley.edu/bpp/) (Business Economics) at Haas School of
Business, UC Berkeley. My interests lie primarily in industrial organization and
microeconomic theory, and my research focuses on understanding the effects of
market power in digital and platform markets.

Prior to my time at UC Berkeley, I worked for several years as a Data Scientist
at [QuantCo](https://www.quantco.com/), combining predictive and causal methods
to build pricing technology. I completed my bachelor's degree at Harvard
University and my master's at the University of Cambridge.

Email: [nversteeg@berkeley.edu](mailto:nversteeg@berkeley.edu)

  </div>

</div>
