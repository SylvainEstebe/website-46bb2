---
title: Photography
layout: page
icon: camera
weight: 2
summary: A curated gallery of my photographic work.
---

## 📷 Gallery with Lightbox

<div class="photo-gallery">

  <a href="#img1">
    <img src="/uploads/DSC08426-Enhanced-SR.jpg" alt="Forest" />
  </a>
  <a href="#img2">
    <img src="/uploads/DSC08429-Enhanced-SR.jpg" alt="City" />
  </a>
  <a href="#img3">
    <img src="/uploads/DSC09046.jpg" alt="Portrait" />
  </a>

</div>

<!-- Lightbox Modals -->
<article id="img1" class="lightbox">
  <a href="#!" class="close"></a>
  <img src="/uploads/DSC08426-Enhanced-SR.jpg" alt="Forest" />
</article>

<article id="img2" class="lightbox">
  <a href="#!" class="close"></a>
  <img src="/uploads/DSC08429-Enhanced-SR.jpg" alt="City" />
</article>

<article id="img3" class="lightbox">
  <a href="#!" class="close"></a>
  <img src="/uploads/DSC09046.jpg" alt="Portrait" />
</article>

<style>
.photo-gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
}

.photo-gallery img {
  width: 300px;
  height: auto;
  border-radius: 8px;
  cursor: zoom-in;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.lightbox {
  display: none;
  position: fixed;
  z-index: 1000;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0, 0, 0, 0.9);
  text-align: center;
  padding-top: 5%;
}

.lightbox img {
  max-width: 90%;
  max-height: 80vh;
}

.lightbox:target {
  display: block;
}

.lightbox .close {
  position: absolute;
  top: 2rem;
  right: 2rem;
  font-size: 2rem;
  color: #fff;
  text-decoration: none;
}
</style>