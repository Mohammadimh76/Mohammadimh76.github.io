---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 4
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

<!-- Publication Item 1 -->
<div class="publication-item">
  
  <div class="pub-image">
    <!-- آدرس عکس خود را اینجا قرار دهید -->
    <img src="/assets/img/Books/Patent_Mockup.jpg" alt="A Step-By-Step Guide to Patenting in Iran" class="img-fluid rounded z-depth-1">
  </div>
  
  <!-- لینک آمازون خود را اینجا قرار دهید -->
  <div class="pub-text" onclick="window.open('https://www.amazon.com/Step-Step-Guide-Patenting-Iran-ebook/dp/B08YKDFC4Q', '_blank')">
    <h4 class="pub-title">A Step-By-Step Guide to Patenting in Iran</h4>
    
    <div class="pub-meta">
      <span class="pub-date">Nov 2020</span> &bull; 
      <span class="pub-authors">M.H. Mohammadi, Ali Karimi, Seyed Yahya Moradi</span>
    </div>
    
    <p class="pub-desc">
      This book aims to acquaint faculty, university students, researchers, and inventors with the step-by-step patenting process in Iran, bridging the gap between innovative ideas and intellectual property protection.
    </p>
    
    <span class="pub-link">View on Amazon &rarr;</span>
  </div>

</div>

---


