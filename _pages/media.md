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
    <figcaption>
      This picture features me and other presenters at the 2026 BEER Symposium held at George Mason University.
    </figcaption>
  </figure>

  <figure>
    <img src="/images/Photo.jpeg" onclick="openLightbox(this)">
    <figcaption></figcaption>
  </figure>

</div>


<!-- Photo Lightbox -->

<div id="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img">
</div>


<h2>Videos</h2>

<div class="video-gallery">

  <div class="video-card" onclick="openVideo()">

    <video muted>
      <source src="/videos/vid.mp4" type="video/mp4">
    </video>

    <div class="play-button">▶</div>

    <p>When your seat is randomly picked and all you can do is spin and pray 😂🎯 …and somehow it lands on BLANKET! 🥳🏆 COS College branded blanket won on Aug. 21, 2026🎉.
</p>

  </div>

</div>


<!-- Video Lightbox -->

<div id="video-lightbox" onclick="closeVideo()">

  <video id="large-video" controls onclick="event.stopPropagation()">
    <source src="/videos/vid.mp4" type="video/mp4">
  </video>

</div>


<style>

/* =========================
   PHOTO GALLERY
   ========================= */

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


/* =========================
   PHOTO LIGHTBOX
   ========================= */

#lightbox {
  position: fixed;
  display: none;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
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


/* =========================
   VIDEO GALLERY
   ========================= */

.video-gallery {
  display: flex;
  justify-content: flex-start;
  gap: 25px;
  margin-top: 20px;
}

.video-card {
  position: relative;
  width: 280px;
  cursor: pointer;
  text-align: center;
}

.video-card video {
  width: 280px;
  height: 170px;
  object-fit: cover;
  border-radius: 10px;
  display: block;
}

.video-card p {
  margin-top: 8px;
  font-size: 15px;
}


/* Play button */

.play-button {
  position: absolute;
  top: 65px;
  left: 115px;
  width: 50px;
  height: 40px;
  background: rgba(0,0,0,0.7);
  color: white;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
}


/* =========================
   LARGE VIDEO
   ========================= */

#video-lightbox {
  position: fixed;
  display: none;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.9);
  justify-content: center;
  align-items: center;
  z-index: 9999;
}

#video-lightbox video {
  max-width: 90%;
  max-height: 90%;
}

</style>


<script>

/* =========================
   PHOTO LIGHTBOX
   ========================= */

function openLightbox(img) {

  const box = document.getElementById("lightbox");
  const boxImg = document.getElementById("lightbox-img");

  box.style.display = "flex";
  boxImg.src = img.src;

}


function closeLightbox() {

  document.getElementById("lightbox").style.display = "none";

}


/* =========================
   VIDEO LIGHTBOX
   ========================= */

function openVideo() {

  const box = document.getElementById("video-lightbox");
  const video = document.getElementById("large-video");

  box.style.display = "flex";

  video.currentTime = 0;

  video.play();

}


function closeVideo() {

  const box = document.getElementById("video-lightbox");
  const video = document.getElementById("large-video");

  video.pause();

  box.style.display = "none";

}

</script>











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




