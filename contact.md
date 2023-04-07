---
title: Contact me
feature_text: |
  ## I'm looking forward to working with you!
feature_image: /assets/photos/feature_img2.jpeg
excerpt: "I'm looking forward to working with you!"
aside: true
---
<!-- Add the Swiper CSS -->
<link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />

<!-- The photo slider -->
<div class="swiper-container">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <a href="/assets/photos/hyehua_my_photo_large.jpeg" data-lightbox="my-photos">
        <img src="/assets/photos/hyehua_my_photo.jpeg" alt="" width="200" height="200">
      </a>
    </div>
    <!-- Add more photos here -->
  </div>
  <!-- Add pagination here -->
  <div class="swiper-pagination"></div>
</div>

<!-- Add the Swiper JavaScript -->
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

<!-- Initialize the Swiper -->
<script>
  var swiper = new Swiper('.swiper-container', {
    pagination: {
      el: '.swiper-pagination',
      clickable: true,
    },
  });
</script>
