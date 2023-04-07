---
title: Contact me
feature_text: |
  Contact me whenever you want
feature_image: /assets/photos/eunhang.jpeg
excerpt: "I'm looking forward to working with you!"
aside: true
---

<div class="photo">
  <a href="/assets/photos/hyehua_my_photo_large.jpeg" data-lightbox="my-photos">
    <img src="/assets/photos/hyehua_my_photo.jpeg" alt="">
  </a>
</div>

<style>
.photo {
  border: 2px solid #ccc;
  border-radius: 50%; /* make the container circular */
  box-shadow: 0 0 5px #ccc;
  display: inline-block;
  margin: 10px;
  padding: 5px;
  width: 70px; /* set the width of the container */
  height: 50px; /* set the height of the container */
  overflow: hidden; /* hide any parts of the image that exceed the container */
}

.photo img {
  display: block;
  max-width: 100%; /* make the image fit inside the container */
  border-radius: 50%; /* make the image circular */
}

.photo a {
  display: block;
  position: relative;
}

.photo a:before {
  content: "";
  display: block;
  position: absolute;
  top: -10px;
  left: -10px;
  right: -10px;
  bottom: -10px;
  border: 5px solid #fff;
  border-radius: 50%; /* make the border circular */
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  opacity: 0;
  transition: opacity 0.2s ease;
}

.photo a:hover:before {
  opacity: 1;
}
</style>

<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.1/js/lightbox.min.js"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.1/css/lightbox.min.css">
