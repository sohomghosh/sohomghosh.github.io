---
layout: page
title: Photo Gallery
permalink: /gallery/
description: A visual journey through my life. Explore photo highlights spanning academic and corporate milestones, adventure sports, running, and musical pursuits.
nav: true
nav_order: 7
---

<style>
  .photo-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 16px;
    padding: 16px 0;
  }
  
  .photo-gallery img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease-in-out;
  }

  .photo-gallery img:hover {
    transform: scale(1.02);
  }
</style>

<div class="photo-gallery">
  <img src="{{ '/assets/img/1.png' | relative_url }}" alt="My Life 🙂">
  <img src="{{ '/assets/img/2.png' | relative_url }}" alt="Cycling">
  <img src="{{ '/assets/img/3.png' | relative_url }}" alt="Running">
  <img src="{{ '/assets/img/4.png' | relative_url }}" alt="Harmonica and Cajon">
  <img src="{{ '/assets/img/5.png' | relative_url }}" alt="Trekking">
  <img src="{{ '/assets/img/7.png' | relative_url }}" alt="PhD Life">
  <img src="{{ '/assets/img/8.png' | relative_url }}" alt="Corporate Life">
  <img src="{{ '/assets/img/9.png' | relative_url }}" alt="Adventure Sports">
</div>
