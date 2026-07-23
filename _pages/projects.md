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
        <li>Developed an end-to-end AI system at the intersection of Computer Vision and NLP to generate contextually relevant textual descriptions for unstructured image data.</li>
        <li>Architected a hybrid neural network utilizing Convolutional Neural Networks (CNN) for robust feature extraction and Long Short-Term Memory (LSTM) networks for accurate sequence generation.</li>
        <li>Trained, optimized, and validated the deep learning model on the Flickr8k dataset, managing complex data preprocessing pipelines for sequential text tokens and images.</li>
        <li>Focused on writing clean, modular, and object-oriented Python code to ensure high system maintainability and scalability.</li>
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
        <li>Designed, trained, and deployed an automated Speech Recognition system to process sequential audio streams and map extracted acoustic features to text using deep neural networks.</li>
        <li>Built a robust data preprocessing pipeline to handle raw audio signals and bridge the gap between machine learning performance and user experience.</li>
        <li>Engineered a human-centered, interactive web dashboard using Streamlit, allowing end-users to seamlessly record audio, upload files, and view real-time transcriptions.</li>
        <li>Applied UX principles and modular code architecture (with Git version control) to ensure visual consistency, accessibility, and readiness for CI/CD integration.</li>
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
        <li>Engineered a production-ready deep learning application for the semantic segmentation of breast cancer pathology images, transforming academic research into a scalable software product.</li>
        <li>Developed and fine-tuned a U-Net architecture to precisely delineate tissue boundaries and detect tumor regions, maximizing diagnostic potential.</li>
        <li>Packaged the trained PyTorch model into a high-performance RESTful API using FastAPI, and containerized the backend using Docker for isolated, cloud-ready deployment.</li>
        <li>Conceptualized an intuitive frontend interface leveraging Product Design principles, enabling physicians to upload scans and analyze segmentation masks without technical friction.</li>
      </ul>
    </div>
    
    <span class="pub-link">View Project &rarr;</span>
  </div>

</div>


