---
title: "Mind Lab | Department of Mechanical Engineering at Binghamton University"
layout: homelay
excerpt: "Mind Lab | Department of Mechanical Engineering at Binghamton University"
sitemap: false
permalink: /
---

<!--<section style="padding: 8rem 2rem; text-align: center; background-color: #006B54; color: white;">
  <h1 style="font-size: 5rem; font-weight: 800; margin: 0; color: white;">MIND Lab</h1>
  <p style="font-size: 2.0rem; margin-top: 1rem; color: white;">Machine Learning for Materials & Molecules</p>
  <p style="font-size: 1.7rem; font-weight: 300; margin-top: 0.5rem; color: white;">
    Department of Mechanical Engineering at Binghamton University
  </p>
</section>-->

<section style="
  padding: 8rem 2rem;
  text-align: center;
  color: white;
  background-image: url('{{ site.baseurl }}/images/binghamton_campus.jpeg');
  background-size: cover;
  background-position: center;
">
</section>

<section style="padding: 2rem 1rem; max-width: 900px; margin: auto;">
  <p style="font-size: 1.7rem;">
    We are the <strong>MIND Lab</strong>, based in the <a href="https://www.binghamton.edu/mechanical-engineering/">Department of Mechanical Engineering</a> at
    <a href="https://www.binghamton.edu">Binghamton University</a>. Our research develops <strong>artificial intelligence</strong> and
    <strong>atomistic simulation</strong> methods to understand and design materials for <strong>interfacial engineering</strong>,
    <strong>microelectronics reliability</strong>, <strong>energy technologies</strong>, and <strong>environmental sustainability</strong>.
  </p>
  {% if site.joint_affiliation_text %}
  <p style="font-size: 1.15rem; margin-top: 0.6rem;">
    {% if site.joint_affiliation_url %}
      <a href="{{ site.joint_affiliation_url }}" style="color: inherit; text-decoration: underline;">
        {{ site.joint_affiliation_text }}
      </a>
    {% else %}
      {{ site.joint_affiliation_text }}
    {% endif %}
  </p>
  {% else %}
  <p style="font-size: 1.15rem; margin-top: 0.6rem;">
    <a href="https://www.binghamton.edu/mse/graduate/" style="color: inherit; text-decoration: underline;">
      Jointly affiliated with the Materials Science &amp; Engineering (MSE) Program
    </a>
  </p>
  {% endif %}
</section>

{::nomarkdown}
{% include home_carousel.html %}
{:/nomarkdown}

<h2>Research Directions</h2>

<h3>AI for Interfacial Engineering and Microelectronics Reliability</h3>
<p>
We develop machine learning and atomistic simulation methods to understand adhesion, fracture, and reliability in materials interfaces, including hybrid bonding and Cu–dielectric interfaces for advanced microelectronics packaging.
</p>

<h3>AI-Driven Materials Characterization</h3>
<p>
We combine spectroscopy simulation, neural networks, and generative models to infer atomic structures and structure–property relationships in disordered and complex materials.
</p>

<h3>Energy and Environmental Materials</h3>
<p>
We use quantum chemistry, molecular simulation, and data-driven modeling to study materials and molecular systems relevant to clean energy, catalysis, separations, and PFAS degradation.
</p>
