---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 3
---

<!-- Main container with separate hover for text only -->
<div style="clear: both; display: flex; align-items: flex-start;">
  <!-- Image section without hover effect -->
  <div style="flex-shrink: 0; padding-right: 3%;">
    <img src="/assets/img/Books/Patent_Mockup.jpg" alt="Science class image" class="img-fluid rounded z-depth-1" style="width: 100%; height: auto;">
  </div>
  
  <!-- Text container with hover and click functionality -->
  <div onclick="window.open('', '_blank')" style="cursor: pointer; padding: 10px; transition: background-color 0.3s; width: 100%;">
    <h4>A Step-By-Step Guide to Patenting in Iran</h4>
    <h6>November, 1, 2020</h6>
    <p>
      This book aims to acquaint faculty and university students, and all the researchers and inventors, interested in registering their designs, with the patenting process in Iran...<br><br>
      <a href="" target="_blank" style="color: #0073e6; text-decoration: underline;" onclick="event.stopPropagation();">[Read more]</a>.
    </p>
  </div>
</div>

<!-- CSS for hover effect on the text container only -->
<style>
  /* Hover effect on the text container only */
  div[onclick]:hover {
    background-color: #f0f0f0; /* Light gray background on hover */
  }
</style>

<br>






























<!--
<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
-->
