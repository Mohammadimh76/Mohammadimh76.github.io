---
layout: page
permalink: /patents/
title: patents
nav: true
nav_order: 3
---

<!-- اگر این کدهای استایل را قبلاً در صفحه گذاشته‌اید، نیازی به کپی مجدد این بخش <style> نیست -->
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

<!-- Patent Item 1 -->
<div class="publication-item">
  
  <div class="pub-image">
    <!-- آدرس عکس مربوط به پتنت اول را در src جایگزین کنید -->
    <img src="/assets/img/patents/patent_Heterochromia .png" alt="Heterochromia disease detection patent" class="img-fluid rounded z-depth-1">
  </div>
  
  <!-- لینک مربوط به صفحه پتنت را در window.open قرار دهید -->
  <div class="pub-text" onclick="window.open('#', '_blank')">
    <h4 class="pub-title">The system for early detection of Heterochromia disease in the neonates</h4>
    
    <div class="pub-meta">
      <span class="pub-date">2021</span> &bull; 
      <span class="pub-authors">Seyed Yahya Moradi, M.H. Mohammadi</span>
    </div>
    
    <p class="pub-desc">
      <b>Patent No:</b> IR-139850140003011312
    </p>
    
    <span class="pub-link">View Patent &rarr;</span>
  </div>

</div>

<!-- Patent Item 2 -->
<div class="publication-item">
  
  <div class="pub-image">
    <!-- آدرس عکس مربوط به پتنت دوم را در src جایگزین کنید -->
    <img src="/assets/img/patents/patent_Pocket_Injective.png" alt="Pocket Protector Patent" class="img-fluid rounded z-depth-1">
  </div>
  
  <!-- لینک مربوط به صفحه پتنت را در window.open قرار دهید -->
  <div class="pub-text" onclick="window.open('#', '_blank')">
    <h4 class="pub-title">Pocket Protector Of Sensitive Injective And Inhalant Vials Against Temperature And Impact Changes</h4>
    
    <div class="pub-meta">
      <span class="pub-date">2020</span> &bull; 
      <span class="pub-authors">Seyed Yahya Moradi, M.H. Mohammadi, Pejman Mohammadi</span>
    </div>
    
    <p class="pub-desc">
      <b>Patent No:</b> IR-139850140003011419
    </p>
    
    <span class="pub-link">View Patent &rarr;</span>
  </div>

</div>
