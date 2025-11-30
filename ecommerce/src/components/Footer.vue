<template>
  <div class="footer">
    <div class="footer-section-1">
      <div class="megamart-text">MegaMart</div>
      <div class="contact-us-text">Contact Us</div>
      <img src="/contact/60.svg" alt="contact" class="contact-icon" />
      <img src="/contact/61.svg" alt="contact" class="contact-icon-2" />
      <div class="download-app-text">Download App</div>
      <img src="/contact/200.svg" alt="download" class="download-icon" />
    </div>
    <div class="footer-section-2">
      <div class="popular-categories-text">Most Popular Categories</div>
      <div class="category-divider"></div>
      <img src="/aynur/dairy.svg" alt="dairy" class="dairy-icon" />
    </div>
    <div class="footer-section-3">
      <div class="customer-services-text">Customer Services</div>
      <div class="services-divider"></div>
      <img src="/aynur/return.svg" alt="return" class="return-icon" />
    </div>
    <div class="footer-bottom-divider"></div>
    <img src="/aynur/mask.svg" alt="mask" class="mask-icon" />
  </div>
</template>

<script setup>

</script>

<style scoped>
.footer {
  position: fixed;
  left: 0;
  top: 2343px;
  width: 1440px;
  height: 592px;
  background: #008ECC;
}

.megamart-text {
  position: absolute;
  left: 170px;
  top: 100px;
  width: 217px;
  height: 44px;
  color: #FFFFFF;
  font-size: 72px;
  font-weight: 700;
  font-family: 'Arial', sans-serif;
  cursor: pointer;
  transition: text-shadow 0.3s ease;
  -webkit-text-stroke: 1px #000000;
}

.megamart-text:hover {
  text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.3);
}

.contact-us-text {
  position: absolute;
  left: 190px;
  top: 220px;
  width: 200px;
  height: 20px;
  color: #FFFFFF;
  font-size: 36px;
  font-weight: 400;
  white-space: nowrap;
}

.contact-icon {
  position: absolute;
  left: 190px;
  top: 300px;
  width: 217px;
  height: 56px;
  filter: brightness(0) invert(1);
}

.contact-icon-2 {
  position: absolute;
  left: 190px;
  top: 376px;
  width: 217px;
  height: 56px;
  filter: brightness(0) invert(1);
}

.download-app-text {
  position: absolute;
  left: 190px;
  top: 462px;
  width: 200px;
  height: 20px;
  color: #FFFFFF;
  font-size: 36px;
  font-weight: 400;
  white-space: nowrap;
}

.download-icon {
  position: absolute;
  left: 190px;
  top: 528px;
  width: 378px;
  height: auto;
}

.popular-categories-text {
  position: absolute;
  left: 638px;
  top: 120px;
  width: 350px;
  height: 20px;
  color: #FFFFFF;
  font-size: 28px;
  font-weight: 400;
  white-space: nowrap;
}

.category-divider {
  position: absolute;
  left: 638px;
  top: 155px;
  width: 320px;
  height: 2px;
  background: #FFFFFF;
}

.dairy-icon {
  position: absolute;
  left: 638px;
  top: 187px;
  width: 200px;
  height: auto;
}

.customer-services-text {
  position: absolute;
  left: 1040px;
  top: 120px;
  width: 280px;
  height: 20px;
  color: #FFFFFF;
  font-size: 28px;
  font-weight: 400;
  white-space: nowrap;
}

.services-divider {
  position: absolute;
  left: 1040px;
  top: 155px;
  width: 250px;
  height: 2px;
  background: #FFFFFF;
}

.return-icon {
  position: absolute;
  left: 1040px;
  top: 187px;
  width: 260px;
  height: auto;
}

.mask-icon {
  position: absolute;
  right: 0px;
  top: 0px;
  width: 170px;
  height: auto;
  z-index: 10;
}

.footer-bottom-divider {
  position: absolute;
  left: 120px;
  top: 584px;
  width: 1200px;
  height: 0.5px;
  background: #FFFFFF;
}
</style>
