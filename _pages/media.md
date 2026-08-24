---
layout: archive
title: "Academic Gallery"
permalink: /media/
author_profile: true
---



Below are selected moments from conferences, teaching, and research activities.

<div class="gallery">

  <figure>
    <img src="/images/BEERS_Talks.jpg" onclick="openLightbox(this)">
    <figcaption>This picture features me and other presenters at the 2026 BEER Symposium held at George Mason University </figcaption>
  </figure>

  <figure>
    <img src="/images/Photo.jpeg" onclick="openLightbox(this)">
    <figcaption></figcaption>
  </figure>

</div>

<!-- Lightbox -->
<div id="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img">
</div>

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.gallery img {
  width: 250px;     
  height: auto;
  border-radius: 10px;
  cursor: pointer;
  transition: transform 0.2s ease;
  display: block;
  margin: 0 auto;
}

.gallery img:hover {
  transform: scale(1.03);
}

figcaption {
  text-align: center;
  font-size: 14px;
  margin-top: 6px;
  color: #555;
}

/* Lightbox */
#lightbox {
  position: fixed;
  display: none;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0,0,0,0.85);
  justify-content: center;
  align-items: center;
  z-index: 999;
}

#lightbox img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 10px;
}
</style>

<script>
function openLightbox(img) {
  const box = document.getElementById("lightbox");
  const boxImg = document.getElementById("lightbox-img");
  box.style.display = "flex";
  boxImg.src = img.src;
}

function closeLightbox() {
  document.getElementById("lightbox").style.display = "none";
}



.video-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 300px));
  gap: 25px;
  justify-content: center;
  margin-top: 20px;
}

.video-card video {
  width: 300px;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
  cursor: pointer;
}

.video-card p {
  text-align: center;
  margin-top: 8px;
}
</script>


<h2>Videos</h2>

<div class="video-gallery">

  <div class="video-card">
    <video controls>
      <source src="/videos/conference-talk.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>

    <p><strong>Conference Presentation</strong></p>
  </div>

</div>



















**Links**
=====
These are  some links I found helpful

**Universities**
- [George Mason University(GMU)](https://www.gmu.edu/)
- [Africa Institute for Mathematical Sciences(AIMS) Ghana](https://aims.edu.gh/)
- [University of Cape Coast(UCC)](https://ucc.edu.gh/)

**National Mathematical Organizations**
- [Society for Industrial and Applied Mathematics(SIAM)](https://www.siam.org/)
- [Society of Mathematical Biology(SMB)](https://smb.org/)




