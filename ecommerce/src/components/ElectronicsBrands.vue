<template>
  <div class="electronics-section">
    <h2 class="section-title">
      Top <span class="highlight">Electronics Brands</span>
    </h2>
    <a href="#" class="view-all">
      View All <span class="arrow">></span>
    </a>
    <hr class="divider">
    <div class="brands-row">
      <img src="/brands/Group 50.svg" alt="Brand" class="brand-logo">
      <img src="/brands/Group 51.svg" alt="Brand" class="brand-logo">
      <img src="/brands/Group 52.svg" alt="Brand" class="brand-logo">
    </div>
    <img src="/brands/Group 53 (1).svg" alt="Brand" class="brand-extra">
  </div>
</template>

<script setup>

</script>

<style scoped>
.electronics-section {
  position: fixed;
  top: 1495px;
  left: 0;
  width: 1440px;
  padding-top: 40px;
}

.section-title {
  position: absolute;
  left: 120px;
  top: 20px;
  width: 245px;
  height: 46px;
  font-size: 24px;
  font-weight: 500;
  color: #666666;
  margin: 0;
  line-height: 46px;
  white-space: nowrap;
  border-bottom: 2px solid #008ECC;
  padding-bottom: 5px;
}

.section-title .highlight {
  color: #008ECC;
}

.view-all {
  position: absolute;
  left: 1238px;
  top: 26px;
  width: 82px;
  height: 18px;
  font-size: 14px;
  color: #666666;
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 4px;
}

.view-all .arrow {
  color: #008ECC;
}

.divider {
  position: absolute;
  top: 66px;
  left: 0;
  width: 1320px;
  height: 1px;
  background-color: #D9D9D9;
  border: none;
  margin: 0;
}

.brands-row {
  position: absolute;
  top: 90px;
  left: 70px;
  display: flex;
  gap: 0;
}

.brand-logo {
  width: 430px;
  height: 230px;
  object-fit: contain;
}

.brand-extra {
  position: absolute;
  left: 663px;
  top: 263px;
  width: 114px;
  height: 8px;
  object-fit: contain;
}
</style>
