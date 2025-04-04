---
layout: splash
title: "Daniel Zhong"
permalink: /
header:
  overlay_image: /assets/images/BG1.gif
  overlay_filter: "0.6"
  caption: "3D Graphics Programmer & Game Developer"
  actions:
    - label: "Projects"
      url: "/graphic-project/"
    - label: "Resume"
      url: "/assets/resume.pdf"
excerpt: "3D Graphics Programmer & Game Developer"
sitemap: false
---

<!-- Add a static fallback background first -->
<div id="header-bg" class="splash-bg" style="background-image: url('/assets/images/BG1.png');"></div>

<!-- Then load GIF smoothly after -->
<script>
document.addEventListener("DOMContentLoaded", function() {
  const bg = document.getElementById("header-bg");
  const gif = new Image();
  gif.src = "/assets/images/BG1.gif";

  gif.onload = function () {
    bg.style.transition = "background-image 0.5s ease-in-out";
    bg.style.backgroundImage = "url('/assets/images/BG1.gif')";
  };
});
</script>
