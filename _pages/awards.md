---
layout: page
permalink: /awards/
title: awards
nav: true
nav_order: 5
---

<style>
  /* Container for the whole item */
  .publication-item {
    display: flex;
    align-items: flex-start;
    gap: 24px;
    margin-bottom: 2rem;
  }

  /* Image styling */
  .pub-image {
    flex-shrink: 0;
    width: 160px; /* عرض تصویر ثابت برای دسکتاپ */
  }

  .pub-image img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  }

  /* Text Container with Hover Effects */
  .pub-text {
    cursor: pointer;
    padding: 16px 20px;
    border-radius: 12px;
    background-color: transparent;
    transition: background-color 0.3s ease, transform 0.3s ease;
    width: 100%;
  }

  /* Hover Micro-interaction */
  .pub-text:hover {
    background-color: #f8f9fa;
    transform: translateX(6px);
  }

  /* Typography */
  .pub-title {
    margin: 0 0 8px 0;
    font-size: 1.25rem;
    font-weight: 600;
    color: #0066CC;
  }

  .pub-meta {
    font-size: 0.85rem;
    color: #6c757d;
    margin-bottom: 12px;
    font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  }

  .pub-desc {
    margin: 0 0 16px 0;
    color: #4a4a4a;
    line-height: 1.6;
  }

  /* Call to Action Link */
  .pub-link {
    font-size: 0.95rem;
    font-weight: 500;
    color: #0066cc;
    text-decoration: none;
    transition: color 0.2s ease;
  }

  .pub-text:hover .pub-link {
    text-decoration: underline;
    color: #004c99;
  }

  /* Mobile Responsiveness */
  @media (max-width: 768px) {
    .publication-item {
      flex-direction: column;
      gap: 16px;
    }
    
    .pub-image {
      width: 120px;
      margin-left: 20px;
    }
    
    .pub-text:hover {
      transform: translateX(0);
    }
  }
</style>

<br>

<!-- Publication/Award Item 2 (7th Marathon) -->
<div class="publication-item">
  
  <div class="pub-image">
    <img src="/assets/img/7th-Marathon/7th-Marathon-1.jpg" alt="7th Mobile Programming Marathon" class="img-fluid rounded z-depth-1">
  </div>
  
  <div class="pub-text" onclick="window.open('https://mohammadimh76.github.io/awards/7thMarathon', '_blank')">
    <h4 class="pub-title">2<sup>nd</sup> Team Rank, 7<sup>th</sup> Mobile Programming Marathon</h4>
    
    <div class="pub-meta">
      <span class="pub-date">Sep 2019</span> &bull; 
      <span class="pub-authors">Team Chelesme: Hadi Beigy, M.H. Mohammadi, S.A.A. Moeini</span>
    </div>
    
    <p class="pub-desc">
      Honor description 2<sup>nd</sup> Team Rank, 7<sup>th</sup> Mobile Programming Marathon along with the "Chelesme" team members, 85 teams participated from Iran, the Sharif University of Technology, Tehran, Iran.
    </p>
    
    <span class="pub-link">Read more &rarr;</span>
  </div>

</div>

<!-- Publication/Award Item 3 (4th Marathon) -->
<div class="publication-item">
  
  <div class="pub-image">
    <img src="/assets/img/4th-Marathon/4thMarathon_6.jpg" alt="4th Mobile Programming Marathon" class="img-fluid rounded z-depth-1">
  </div>
  
  <div class="pub-text" onclick="window.open('https://mohammadimh76.github.io/awards/4thMarathon', '_blank')">
    <h4 class="pub-title">3<sup>rd</sup> Team Rank, 4<sup>th</sup> Mobile Programming Marathon</h4>
    
    <div class="pub-meta">
      <span class="pub-date">Sep 2017</span> &bull; 
      <span class="pub-authors">Team Yakhmak: Hadi Beigy, M.H. Mohammadi, S.A.A. Moeini</span>
    </div>
    
    <p class="pub-desc">
      Honor description 3<sup>rd</sup> Team Rank, 4<sup>th</sup> Mobile Programming Marathon along with the "Yakhmak" team members, 90 teams participated from Iran, the Sharif University of Technology, Tehran, Iran.
    </p>
    
    <span class="pub-link">Read more &rarr;</span>
  </div>

</div>

<!-- Publication/Award Item 4 (Sanjesh) -->
<div class="publication-item">
  
  <div class="pub-image">
    <img src="/assets/img/sanjesh.jpg" alt="Iran National Organization of Educational Testing" class="img-fluid rounded z-depth-1">
  </div>
  
  <div class="pub-text" onclick="window.location.href='https://mohammadimh76.github.io/awards/';">
    <h4 class="pub-title">Iran National Organization of Educational Testing</h4>
    
    <div class="pub-meta">
      <span class="pub-date">Jun 2015</span>
    </div>
    
    <p class="pub-desc">
      Ranked in the top 2% participants in the nationwide university entrance examination in 2015 Mathematics and Physics field for entering the undergraduate program among more than 180,000 students.
    </p>
    
    <span class="pub-link">View Details &rarr;</span>
  </div>

</div>
