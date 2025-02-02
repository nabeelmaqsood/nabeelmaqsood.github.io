---
permalink: /
title: " "
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Global Styles */
  body {
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    color: #333;
    background-color: #fafafa;
    margin: 0;
    padding: 0;
    line-height: 1.65;
  }
  .container {
    width: 90%;
    max-width: 900px;
    margin: 0 auto;
    padding: 2rem 1rem;
  }
  /* Headers */
  h1, h2 {
    font-weight: 700;
    color: #222;
    margin-bottom: 0.5rem;
  }
  h1 {
    font-size: 2.5rem;
    text-align: center;
    margin-bottom: 1rem;
  }
  h2 {
    font-size: 1.8rem;
    margin-top: 2rem;
    margin-bottom: 1rem;
    border-bottom: 2px solid #ddd;
    padding-bottom: 0.3rem;
  }
  /* Job Market Tagline */
  .job-market {
  text-align: center;
  font-size: 1.125rem;
  margin-bottom: 2rem;
  color: #2C3E50;
}

  /* Paragraphs */
  p {
    font-size: 1.125rem;
    text-align: justify;
    margin-bottom: 1.5rem;
  }
  /* Custom Bullet List */
  ul.custom-bullets {
    list-style: none;
    padding-left: 0;
    margin-bottom: 1.5rem;
  }
  ul.custom-bullets li {
    position: relative;
    padding-left: 2.5rem;
    margin-bottom: 0.75rem;
    font-size: 1.125rem;
  }
  ul.custom-bullets li::before {
    position: absolute;
    left: 0;
    font-size: 1.125rem;
  }
  ul.custom-bullets li.bullet-judiciary::before {
    content: "⚖️";
  }
  ul.custom-bullets li.bullet-policy::before {
    content: "📈";
  }
  ul.custom-bullets li.bullet-structural::before {
    content: "📊";
  }
  /* Education Section */
  .education {
    margin-top: 2rem;
  }
  .education-item {
    margin-bottom: 1.5rem;
  }
  .education-item sub {
    display: block;
    font-size: 0.95rem;
    color: #666;
    margin-top: 0.3rem;
  }
  /* Refined, Compact Contact Form */
  .contact-form {
    background: #fff;
    padding: 1rem;
    border: 1px solid #e0e0e0;
    border-radius: 6px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    margin: 2rem auto;
    max-width: 400px;
  }
  .contact-form label {
    font-size: 1rem;
    margin-bottom: 0.25rem;
    display: block;
    color: #333;
  }
  .contact-form input,
  .contact-form textarea {
    width: 100%;
    padding: 0.6rem;
    margin-bottom: 0.75rem;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-size: 1rem;
  }
  .contact-form textarea {
    resize: vertical;
    min-height: 120px;
  }
  .contact-form button {
    background-color: #007aff;
    color: #fff;
    border: none;
    padding: 0.6rem 1.5rem;
    font-size: 1rem;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
    display: block;
    width: 100%;
    max-width: 200px;
    margin: 0.5rem auto 0;
  }
  .contact-form button:hover {
    background-color: #005bb5;
  }
  /* Contact Info */
  .contact-info {
    text-align: center;
    font-size: 1.125rem;
    margin-top: 1.5rem;
    font-family: 'Avenir', 'Helvetica Neue', Helvetica, Arial, sans-serif;
    font-weight: 700;
    line-height: 1.8;
  }
  .contact-info strong {
    font-weight: 600;
  }
  /* Responsive Adjustments */
  @media (max-width: 600px) {
    h1 {
      font-size: 2rem;
    }
    h2 {
      font-size: 1.5rem;
    }
    p, li, .job-market, .contact-info {
      font-size: 1rem;
    }
    .contact-form {
      padding: 0.75rem;
    }
    .contact-form input,
    .contact-form textarea {
      font-size: 1rem;
      padding: 0.5rem;
    }
    .contact-form button {
      font-size: 1rem;
      padding: 0.5rem 1.5rem;
    }
  }
</style>

<div class="container">
  <!-- Header Section -->
  <h1>Welcome to my website.</h1>
  <p class="job-market">I am on the 2024/25 job market.</p>
  
  <!-- About & Research -->
  <p>
    I am an applied macroeconomist specializing in Development Economics, Labour Economics, and the Economics of Institutions—particularly legal and judicial systems. I employ large datasets for developing causal inference.
  </p>
  
  <p>
    My Doctoral research focuses on three areas:
  </p>
  
  <ul class="custom-bullets">
    <li class="bullet-judiciary"><strong>Frontline Judiciary:</strong> Analyzing how local courts affect labour market outcomes and economic development.</li>
    <li class="bullet-policy"><strong>Economic Policy Impacts:</strong> Assessing the effects of Demonetization on firms and informality.</li>
    <li class="bullet-structural"><strong>Structural Transformation:</strong> Evaluating production technologies and resource misallocation.</li>
  </ul>
  
  <!-- Education -->
  <h2>Education</h2>
  <div class="education">
    <div class="education-item">
      &#127891; PhD in Economics, 2024<br>
      <sub>Deakin University, Melbourne, Australia</sub>
    </div>
    <div class="education-item">
      &#127891; MS Economics & Statistics, 2020<br>
      <sub>Korea University, Seoul, Rep. of South Korea</sub>
    </div>
    <div class="education-item">
      &#127891; BS Economics, 2015<br>
      <sub>Quaid i Azam University, Islamabad, Pakistan</sub>
    </div>
  </div>
  
  <!-- Contact -->
  <h2>Contact</h2>
  <form action="https://formspree.io/f/mpwaadvz" method="POST" class="contact-form">
    <label for="name">Your Name</label>
    <input type="text" name="name" id="name">
    
    <label for="email">Your Email</label>
    <input type="email" name="email" id="email">
    
    <label for="message">Your Message</label>
    <textarea name="message" id="message"></textarea>
    
    <button type="submit">Send</button>
  </form>
  
  <p class="contact-info">
    <strong>📞</strong> <span style="margin-left: 0.5rem;">61452420994</span><br>
    <strong>📍</strong> <span style="margin-left: 0.5rem;">28/60 Elgar Rd, Burwood, VIC 3125</span><br>
    <strong>🏢</strong> <span style="margin-left: 0.5rem;">EA Building, Level 2, EA 2.40</span>
  </p>
</div>
