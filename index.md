---
layout: default
title: David Zegarra
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

# ABOUT ME
Hi!, I'm a professional in Electronics with +20 years in the field. A self-taught programmer, these days I navigate the embedded circuit and web interface domains, building at the intersection of embedded systems, IoT/RFID, and web development. An advocate of good documentation, because it's what keeps a project alive and shareable.

# RECENT PROJECTS
Categorized by domain. 

## Web Development
* [🎉 Confetti Challenge](https://zrdavid.github.io/Confetti_Challenge/) - HTML Canvas exploration: Understanding 2D graphics primitives before moving to Three.js
* [🌀 3D Fan Simulation](https://zrDavid.github.io/Fan_Control/) - Three.js visualization prototype: Exploring real-time 3D rendering for industrial applications.

## Embedded Systems:


<!-- FontAwesome CDN import to fix the empty squares -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<!-- Right-side floating sidebar (Desktop) -->
<div class="social-sidebar-right">
  {% for link in site.social %}
    <a href="{{ link.url }}" target="_blank" rel="noopener noreferrer">
      <i class="fa-brands {{ link.icon }}"></i>
    </a>
  {% endfor %}
</div>

<!-- Footer bar (Mobile) -->
<div class="social-mobile-footer">
  {% for link in site.social %}
    <a href="{{ link.url }}" target="_blank" rel="noopener noreferrer">
      <i class="fa-brands {{ link.icon }}"></i>
    </a>
  {% endfor %}
</div>
