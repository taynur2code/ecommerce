<template>
  <div class="deal-section">
    <h2 class="deal-title">
      Grab the best deal on <span class="highlight">Smartphones</span>
    </h2>
    <a href="#" class="view-all">
      View All <span class="arrow">></span>
    </a>
    <hr class="divider">
    <div class="products-row">
      <ProductCard product-image="/productdeal/image 3.svg" />
      <ProductCard 
        product-image="/productdeal/image 3 (1).svg"
        product-name="Galaxy M13 (4GB | 64 GB )"
        current-price="₹10499"
        original-price="₹14999"
        save-amount="₹4500"
      />
      <ProductCard 
        product-image="/productdeal/image 3 (2).svg"
        product-name="Galaxy M33 (4GB | 64 GB )"
        current-price="₹16999"
        original-price="₹24999"
        save-amount="₹8000"
      />
      <ProductCard 
        product-image="/productdeal/image 3 (3).svg"
        product-name="Galaxy M53 (4GB | 64 GB )"
        current-price="₹31999"
        original-price="₹40999"
        save-amount="₹9000"
      />
      <ProductCard 
        product-image="/productdeal/image 3 (4).svg"
        product-name="Galaxy S22 Ultra"
        current-price="₹67999"
        original-price="₹85999"
        save-amount="₹18000"
      />
    </div>
  </div>
</template>

<script setup>
import ProductCard from './ProductCard.vue'
</script>

<style scoped>
.deal-section {
  position: fixed;
  top: 606px;
  left: 0;
  width: 1440px;
  height: 500px;
  padding-top: 50px;
}

.deal-title {
  position: absolute;
  left: 120px;
  top: 40px;
  width: 378px;
  height: 30px;
  font-size: 24px;
  font-weight: 500;
  color: #666666;
  margin: 0;
  line-height: 30px;
  white-space: nowrap;
  border-bottom: 2px solid #008ECC;
  padding-bottom: 5px;
}

.deal-title .highlight {
  color: #008ECC;
}

.view-all {
  position: absolute;
  left: 1238px;
  top: 46px;
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
  top: 71px;
  left: 0;
  width: 1320px;
  height: 1px;
  background-color: #D9D9D9;
  border: none;
  margin: 0;
}

.products-row {
  position: absolute;
  top: 90px;
  left: 120px;
  display: flex;
  gap: 15px;
}
</style>
