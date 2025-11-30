<template>
  <div class="daily-essentials-section">
    <h2 class="section-title">
      Daily <span class="highlight">Essentials</span>
    </h2>
    <a href="#" class="view-all">
      View All <span class="arrow">></span>
    </a>
    <hr class="divider">
    <div class="cards-row">
      <EssentialsCard product-image="/productdaily/fruit.svg" card-title="Daily Essentials" />
      <EssentialsCard product-image="/productdaily/fruit1.svg" card-title="Vegetables" />
      <EssentialsCard product-image="/productdaily/fruit2.svg" card-title="Fruits" />
      <EssentialsCard product-image="/productdaily/fruit3.svg" card-title="Strawberry" />
      <EssentialsCard product-image="/productdaily/fruit4.svg" card-title="Mango" />
      <EssentialsCard product-image="/productdaily/fruit5.svg" card-title="Cherry" />
    </div>
  </div>
</template>

<script setup>
import EssentialsCard from './EssentialsCard.vue'
</script>

<style scoped>
.daily-essentials-section {
  position: fixed;
  top: 1836px;
  left: 0;
  width: 1440px;
  padding-top: 40px;
}

.section-title {
  position: absolute;
  left: 120px;
  top: 20px;
  width: 167px;
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

.cards-row {
  position: absolute;
  top: 106px;
  left: 120px;
  display: flex;
  gap: 16px;
}
</style>
