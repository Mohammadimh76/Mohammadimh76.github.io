---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
nav_order: 2
---

<!-- CSS Style -->
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

  /* Description and List styling */
  .pub-desc {
    margin: 0 0 16px 0;
    color: #4a4a4a;
    line-height: 1.6;
  }

  .pub-desc ul {
    padding-left: 20px;
    margin-top: 8px;
    margin-bottom: 0;
  }

  .pub-desc li {
    margin-bottom: 6px;
  }

  /* Call to Action Link */
  .pub-link {
    font-size: 0.95rem;
    font-weight: 500;
    color: #0066cc;
    text-decoration: none;
    transition: color 0.2s ease;
    display: inline-block;
    margin-top: 8px;
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

<!-- Project Item 1 -->
<div class="publication-item">
  
  <div class="pub-image">
    <!-- آدرس عکس مربوط به پروژه را جایگزین کنید -->
    <img src="/assets/img/sample.png" alt="Multimodal AI Image Captioning" class="img-fluid rounded z-depth-1">
  </div>
  
  <!-- لینک گیت‌هاب یا جزئیات پروژه را در بخش window.open قرار دهید -->
  <div class="pub-text" onclick="window.open('#', '_blank')">
    <h4 class="pub-title">Multimodal AI: Image Caption Generation System</h4>
    
    <div class="pub-meta">
      <span class="pub-date">May 2026</span> &bull; 
      <span class="pub-authors">Python, CNN, LSTM, NLP, Computer Vision</span>
    </div>
    
    <div class="pub-desc">
      <ul>
        Developed a scalable CNN-LSTM deep learning system in Python to automatically generate contextual text descriptions for images.
      </ul>
    </div>
    
    <span class="pub-link">View Project &rarr;</span>
  </div>

</div>

<!-- Project Item 2 -->
<div class="publication-item">
  
  <div class="pub-image">
    <!-- آدرس عکس مربوط به پروژه را جایگزین کنید -->
    <img src="/assets/img/sample.png" alt="Speech Recognition Web Service" class="img-fluid rounded z-depth-1">
  </div>
  
  <div class="pub-text" onclick="window.open('#', '_blank')">
    <h4 class="pub-title">End-to-End Speech Recognition Web Service</h4>
    
    <div class="pub-meta">
      <span class="pub-date">Sep 2025</span> &bull; 
      <span class="pub-authors">Python, Deep Learning, Streamlit, Git, UI/UX</span>
    </div>
    
    <div class="pub-desc">
      <ul>
        Deployed an end-to-end deep learning speech recognition system with an interactive Streamlit web interface for real-time transcription.
      </ul>
    </div>
    
    <span class="pub-link">View Project &rarr;</span>
  </div>

</div>

<!-- Project Item 3 -->
<div class="publication-item">
  
  <div class="pub-image">
    <!-- آدرس عکس مربوط به پروژه را جایگزین کنید -->
    <img src="/assets/img/sample.png" alt="HealthTech AI Medical Segmentation" class="img-fluid rounded z-depth-1">
  </div>
  
  <div class="pub-text" onclick="window.open('#', '_blank')">
    <h4 class="pub-title">HealthTech AI: Medical Image Segmentation</h4>
    
    <div class="pub-meta">
      <span class="pub-date">Jan 2025</span> &bull; 
      <span class="pub-authors">PyTorch, U-Net, FastAPI, Docker, UI/UX</span>
    </div>
    
    <div class="pub-desc">
      <ul>
          Engineered a containerized U-Net medical imaging application with a FastAPI backend and intuitive UI for semantic segmentation of breast cancer pathology.
        </ul>
    </div>
    
    <span class="pub-link">View Project &rarr;</span>
  </div>

</div>


