---
layout: page
permalink: /about_NZ/
title: Net-Zero Energy & Chemicals
description: Whole systems thinking methods for sustainable future
nav: false
nav_order: 98
horizontal: true
---

**Scope:** Enterprise wide optimization (EWO) is a multiscale paradigm that seeks to optimize in a holistic way the different decision-making grades across contemporary process & chemical industries. By systematically co-optimizing decisions related to production planning, inventory management, process scheduling and control, we can **enhance operational flexibility and resilience**.

<div class="carousel-wrap">
  {% for image in site.data.NZfigs %}
    <div class="carousel-slide">
      <img src="/assets/img/NetZero/{{ image.pic }}" alt="Gallery Image">
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

- Zhou, X., Efthymiadou, M. E., Papageorgiou, L. G., & Charitopoulos, V. M. (2024). Data-driven robust optimisation of hydrogen infrastructure planning under demand uncertainty using a hybrid decomposition method. Applied Energy, 376, 124222.

- Efthymiadou, M. E., Charitopoulos, V. M., & Papageorgiou, L. G. (2024). Optimal hydrogen infrastructure planning for heat decarbonisation. Chemical Engineering Research and Design, 204, 121-136.

- Bounitsis, G. L., & Charitopoulos, V. M. (2024). The value of ammonia towards integrated power and heat system decarbonisation. Sustainable Energy & Fuels, 8(13), 2914-2940.

- Charitopoulos, V. M., Fajardy, M., Chyong, C. K., & Reiner, D. M. (2023). The impact of 100% electrification of domestic heat in Great Britain. Iscience, 26(11)..
