---
layout: splash
title: "Welcome to Daniel Zhong's portfolio"
permalink: /
header:
  overlay_image: /assets/images/BG1.gif
  overlay_filter: "0.57"
  actions:
    - label: "Github"
      url: https://github.com/danielzhong
      new_tab: true
    - label: "Resume"
      url: "/assets/resume.pdf"
      new_tab: true
    - label: "Linkedin"
      url: https://www.linkedin.com/in/danielzhong-/
      new_tab: true
excerpt: "Building 3D Worlds & Game Engines"
sitemap: false
feature_row_projects:
  - image_path: /assets/images/Infinity.jpg
    alt: "Project 1"
    title: "Computer Graphics Projects"
    excerpt: "C++ | WebGPU | OpenGL | Vulkan | CUDA"
    url: "/graphic-project/"
    btn_class: "btn--primary"
    btn_label: "View Project"
  - image_path: https://github.com/user-attachments/assets/13711d9b-c676-47cb-bc3e-32fc15608c2a
    alt: "Project 1"
    title: "Game Development Projects"
    excerpt: "C# | C++ | Unity | UE | VR/AR/MR"
    url: "/game-project/"
    btn_class: "btn--primary"
    btn_label: "View Project"
  - image_path: https://github.com/user-attachments/assets/6a10f996-5322-4617-b7da-c5b593503c45
    alt: "Project 3"
    title: "Game Engine & Tools Projects"
    excerpt: "QT | OpenGL | CDD Software Scripts"
    url: "/tool-project/"
    btn_class: "btn--primary"
    btn_label: "View Project"

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

{% include feature_row id="feature_row_projects" %}