---
layout: page
permalink: /about_EWO/
title: Enterprise Wide Optimization
description: Multi-scale integration schemes for smart manufacturing
nav: false
nav_order: 99
horizontal: true
---

**Aim of EWO:** Enterprise wide optimization (EWO) is a multiscale paradigm that seeks to optimize in a holistic way the different decision-making grades across contemporary process & chemical industries. By systematically co-optimizing decisions related to production planning, inventory management, process scheduling and control, we can **enhance operational flexibility and resilience**.

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

- Lee, Y., Charitopoulos, V. M., Thyagarajan, K., Morris, I., Pinto, J. M., & Papageorgiou, L. G. (2022). Integrated production and inventory routing planning of oxygen supply chains. Chem Eng Res Des, 186, 97-111.

- Marousi, A., Thyagarajan, K., Pinto, J. M., Papageorgiou, L. G., & Charitopoulos, V. M. (2024). Game-theoretic optimisation of supply chain design with customer contracts: The case of industrial gases market. Comput Chem Eng, 184, 108625.

- Charitopoulos, V. M., Papageorgiou, L. G., & Dua, V. (2019). Closed-loop integration of planning, scheduling and multi-parametric nonlinear control. Comput Chem Eng, 122, 172-192.

- Charitopoulos, V. M., Dua, V., & Papageorgiou, L. G. (2017). Traveling salesman problem-based integration of planning, scheduling, and optimal control for continuous processes. Ind Eng Chem Res, 56(39), 11186-11205.
