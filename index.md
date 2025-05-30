---
layout: default
title: Научные достижения России от XIX века до СССР
---

<style>
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    display: flex;
    flex-direction: column;
    height: 100vh;
  }
  
  header {
    background: #f8f9fa;
    padding: 15px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    z-index: 100;
  }
  
  .timeline-container {
    flex-grow: 1;
    position: relative;
    min-height: 0; /* Важно для flex-разметки */
  }
  
  iframe {
    width: 100%;
    height: 100%;
    border: none;
  }
</style>

<header>
  <h1>{{ page.title }}</h1>
  <p>{{ page.description }}</p>
</header>

<div class="timeline-container">
  <iframe 
    src="https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=v2%3A2PACX-1vRXo6uv99PJn_HGrzgkmzx5jVKIlYYoUNyzR0RyVTXDvCJuW9nYlmhMnkTC5hLr3T-hztdsTKuYI5Yh&font=Default&lang=ru&initial_zoom=2&height=100%25"
    allowfullscreen>
  </iframe>
</div>