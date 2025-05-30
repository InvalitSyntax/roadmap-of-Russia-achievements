---
layout: default
title: Главная
---

<style>
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
  }
  .timeline-container {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    z-index: 100;
  }
  .header {
    position: fixed;
    top: 10px;
    left: 10px;
    z-index: 200;
    background: rgba(255,255,255,0.8);
    padding: 5px 10px;
    border-radius: 5px;
  }
</style>

<div class="header">
  <h1>{{ page.title }}</h1>
</div>

<div class="timeline-container">
  <iframe 
    src="https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=v2%3A2PACX-1vRXo6uv99PJn_HGrzgkmzx5jVKIlYYoUNyzR0RyVTXDvCJuW9nYlmhMnkTC5hLr3T-hztdsTKuYI5Yh&font=Default&lang=ru&initial_zoom=2&height=100%25" 
    width="100%"
    height="100%"
    frameborder="0"
    style="border: none;">
  </iframe>
</div>