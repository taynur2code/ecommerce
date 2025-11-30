<template>
  <div class="top-categories-section">
    <h2 class="section-title">
      Shop From <span class="highlight">Top Categories</span>
    </h2>
    <a href="#" class="view-all">
      View All <span class="arrow">></span>
    </a>
    <hr class="divider">
    <div class="categories-row">
      <CategoryCard category-image="/productshoping/image 3 (5).svg" category-name="Mobile" />
      <CategoryCard category-image="/productshoping/image 3 (6).svg" category-name="Cosmetics" />
      <CategoryCard category-image="/productshoping/Ellipse 41.svg" category-name="Electronics" />
      <CategoryCard category-image="/productshoping/image 4.svg" category-name="Furniture" />
      <CategoryCard category-image="/productshoping/image 5.svg" category-name="Watches" />
      <CategoryCard category-image="/productshoping/image 6.svg" category-name="Decor" />
      <CategoryCard category-image="/productshoping/image 7.svg" category-name="Accessories" />
    </div>
  </div>
</template>

<script setup>
import CategoryCard from './CategoryCard.vue'
</script>

<style scoped>
.top-categories-section {
  position: fixed;
  top: 1107px;
  left: 0;
  width: 1440px;
  padding-top: 50px;
}

.section-title {
  position: absolute;
  left: 120px;
  top: 30px;
  width: 378px;
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
  top: 36px;
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
  top: 76px;
  left: 0;
  width: 1320px;
  height: 1px;
  background-color: #D9D9D9;
  border: none;
  margin: 0;
}

.categories-row {
  position: absolute;
  top: 100px;
  left: 120px;
  display: flex;
  gap: 24px;
}
</style>
