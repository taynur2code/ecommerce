<template>
  <div class="carousel-container">
    <button class="carousel-btn carousel-btn-left">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M15 18L9 12L15 6" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
    
    <div class="carousel-card">
      <div class="circle-outer"></div>
      <div class="circle-inner"></div>
      <div class="circle-outer-bottom"></div>
      <div class="circle-inner-bottom"></div>
      <div class="carousel-content">
        <h2 class="carousel-title">Best Deal Online on smart watches</h2>
        <h2 class="carousel-subtitle">SMART WEARABLE.</h2>
        <h2 class="carousel-offer">UP to 80% OFF</h2>
      </div>
      <div class="carousel-dots">
        <div class="dot dot-active"></div>
        <div class="dot"></div>
        <div class="dot"></div>
        <div class="dot"></div>
        <div class="dot"></div>
      </div>
      <img src="/saat.svg" alt="Smart Watch" class="carousel-image" />
    </div>
    
    <button class="carousel-btn carousel-btn-right">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M9 18L15 12L9 6" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
  </div>
</template>

<script setup>

</script>

<style scoped>
.carousel-container {
  position: fixed;
  top: 220px;
  left: 120px;
  width: 1201px;
  height: 316px;
  display: flex;
  align-items: center;
  gap: 0;
}

.carousel-card {
  width: 1201px;
  height: 316px;
  background-color: #212844;
  border-radius: 16px;
  position: relative;
  overflow: hidden;
}

.circle-outer {
  position: absolute;
  left: 750px;
  top: -344px;
  width: 516px;
  height: 516px;
  border-radius: 50%;
  border: 1px solid #3C466B;
  background: transparent;
}

.circle-inner {
  position: absolute;
  left: 768px;
  top: -326px;
  width: 480px;
  height: 480px;
  border-radius: 50%;
  background-color: #2C3454;
}

.circle-outer-bottom {
  position: absolute;
  right: 150px;
  bottom: -150px;
  width: 300px;
  height: 300px;
  border-radius: 50%;
  border: 1px solid #3C466B;
  background: transparent;
}

.circle-inner-bottom {
  position: absolute;
  right: 160px;
  bottom: -140px;
  width: 280px;
  height: 280px;
  border-radius: 50%;
  background-color: #2C3454;
}

.carousel-content {
  position: absolute;
  left: 90px;
  top: 40px;
  width: 574px;
  height: 156px;
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.carousel-title,
.carousel-subtitle,
.carousel-offer {
  color: white;
  margin: 0;
  line-height: 1.2;
}

.carousel-title {
  font-size: 36px;
  font-weight: 600;
}

.carousel-subtitle {
  font-size: 36px;
  font-weight: 700;
}

.carousel-offer {
  font-size: 36px;
  font-weight: 700;
  color: #00D4FF;
}

.carousel-dots {
  position: absolute;
  left: 90px;
  bottom: 47px;
  display: flex;
  gap: 8px;
  align-items: center;
}

.dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: white;
}

.dot-active {
  width: 24px;
  border-radius: 4px;
}

.carousel-image {
  position: absolute;
  right: 90px;
  top: 23px;
  width: 268px;
  height: 270px;
  object-fit: contain;
}

.carousel-btn {
  position: absolute;
  width: 86px;
  height: 86px;
  border-radius: 50%;
  background-color: white;
  border: 8px solid white;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  z-index: 10;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}

.carousel-btn svg {
  filter: drop-shadow(0 0 0 #F3F9FB);
}

.carousel-btn-left {
  left: -43px;
  top: 115px;
}

.carousel-btn-right {
  right: -43px;
  top: 115px;
}

.carousel-btn:hover {
  background-color: #f8f8f8;
}
</style>
