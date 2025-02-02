---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
  /* Container for the CV cards */
  .cv-container {
    max-width: 900px;
    margin: 2rem auto;
    display: flex;
    flex-direction: column;
    gap: 2rem;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    color: #2c3e50;
    padding: 0 1rem;
  }
  /* Each card styling */
  .cv-card {
    background: #fff;
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    padding: 1.5rem;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .cv-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  }
  /* Paragraph inside each card */
  .cv-card p {
    margin: 0;
    font-size: 1rem;
    line-height: 1.6;
  }
  /* Link styling inside cards */
  .cv-card a {
    font-weight: bold;
    text-decoration: none;
    color: #1a73e8;
    border-bottom: 2px solid transparent;
    transition: border-color 0.2s;
  }
  .cv-card a:hover {
    border-color: #1a73e8;
  }
  /* Responsive: two columns on wider screens */
  @media (min-width: 600px) {
    .cv-container {
      flex-direction: row;
    }
    .cv-card {
      flex: 1;
    }
  }
</style>

<div class="cv-container">
  <div class="cv-card">
    <p>
      A bit more about my academic and professional journey. <br>
      <a href="/assets/Nabeel_Maqsood_cv_Feb_2025.pdf" target="_blank">Download my CV here</a>.
    </p>
  </div>
  <div class="cv-card">
    <p>
      Learn about my teaching philosophy and approach. <br>
      <a href="/assets/My Teaching Statement.pdf" target="_blank">See my teaching statement here</a>.
    </p>
  </div>
</div>
