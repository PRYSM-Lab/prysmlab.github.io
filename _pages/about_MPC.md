---
layout: page
permalink: /about_eMPC/
title: (Explicit) Model Predictive Control
description: Fast (data-driven) schemes for model-based control
nav: false
nav_order: 97
horizontal: true
---

**Model Predictive Control:** Enterprise wide optimization (EWO) is a multiscale paradigm that seeks to optimize in a holistic way the different decision-making grades across contemporary process & chemical industries. By systematically co-optimizing decisions related to production planning, inventory management, process scheduling and control, we can **enhance operational flexibility and resilience**.

<div class="carousel-wrap">
  {% for image in site.data.EWOfigs %}
    <div class="carousel-slide">
      <img src="/assets/img/EWO/{{ image.pic }}" alt="Gallery Image">
    </div>
  {% endfor %}
</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const slides = document.querySelectorAll('.carousel-slide');
    let current = 0;

    function showSlide(index) {
      slides.forEach((slide, i) => {
        slide.classList.toggle('active', i === index);
      });
    }

    function nextSlide() {
      current = (current + 1) % slides.length;
      showSlide(current);
    }

    showSlide(current);
    setInterval(nextSlide, 3000); // Change every 3 seconds
  });
</script>

**Our work:** Our work ranges from **integration of control with planning and scheduling** to **integrated production, inventory management and vehicle routing**. Our research spans across two strands. Firstly, the of reinforcement learning with mathematical programming optimisation for studying production networks arising in food and high-value chemicals sectors. Secondly, novel computationally efficient models for integrated planning and scheduling problems arising in EWO.

**Relevant publications:**

- Vega-Zambrano, C., Diangelakis, N. A., & Charitopoulos, V. M. (2025). Data-driven model predictive control for continuous pharmaceutical manufacturing. Int. J. Pharm., 672.

- Charitopoulos, V. M., Papageorgiou, L. G., & Dua, V. (2021). Multi set-point explicit model predictive control for nonlinear process systems. Processes, 9(7), 1156.

- Charitopoulos, V. M., & Dua, V. (2016). Explicit model predictive control of hybrid systems and multiparametric mixed integer polynomial programming. AIChE J., 62(9), 3441-3460.
