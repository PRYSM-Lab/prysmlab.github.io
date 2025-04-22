---
layout: page
permalink: /about_OUU/
title: Optimization under uncertainty
description: Next-generation methods for hedging against uncertainty in decision-making problems
nav: false
nav_order: 96
horizontal: true
---

**Method Development:** We focus on developing computationally efficient and explainable methods for decision-making problems under uncertainty. To this end, we conduct research across the following domains: (i) **Stochastic Programming** for risk-neutral decision-making, (ii) Data-driven & non-convex **Robust Optimization** for safety-critical application areas, e.g. process design and (iii) **Multi-parametric optimization** for online mitigation of uncertainties in operational problems.

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

**Our work:** Our interests lie at the interface of high-fidelity uncertainty modelling and quantification and computationally efficient solutions of the resulting, typically, large-scale problems.

**Scenario Generation for Stochastic Programming**

**Nonconvex Robust Optimization**

**Multi-parametric Optimization**

**Relevant publications:**

- Marousi, A., & Charitopoulos, V. M. (2025). Global and Robust Optimisation for Non-Convex Quadratic Programs. arXiv preprint arXiv:2503.07310.

- Zhou, X., Efthymiadou, M. E., Papageorgiou, L. G., & Charitopoulos, V. M. (2024). Data-driven robust optimisation of hydrogen infrastructure planning under demand uncertainty using a hybrid decomposition method. Applied Energy, 376, 124222.

- Herding, R., Ross, E., Jones, W. R., Endler, E., Charitopoulos, V. M., & Papageorgiou, L. G. (2024). Risk-aware microgrid operation and participation in the day-ahead electricity market. Advances in Applied Energy, 15, 100180.

- Bounitsis, G. L., Papageorgiou, L. G., & Charitopoulos, V. M. (2024). Stable optimisation-based scenario generation via game theoretic approach. Computers & Chemical Engineering, 185, 108646.

- Charitopoulos, V. M., Papageorgiou, L. G., & Dua, V. (2018). Multi-parametric mixed integer linear programming under global uncertainty. Computers & Chemical Engineering, 116, 279-295.
