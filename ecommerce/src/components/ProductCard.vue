<template>
  <div class="product-card">
    <div class="product-image">
      <img :src="productImage" alt="Product">
      <div class="discount-badge">
        <div class="discount-number">56%</div>
        <div class="discount-text">OFF</div>
      </div>
    </div>
    <div class="product-info">
      <h3 class="product-name">{{ productName }}</h3>
      <div class="price-container">
        <span class="current-price">{{ currentPrice }}</span>
        <span class="original-price">{{ originalPrice }}</span>
      </div>
      <hr class="price-divider">
      <div class="save-info">
        Save - {{ saveAmount }}
      </div>
    </div>
  </div>
</template>

<script setup>
import { defineProps } from 'vue'

const props = defineProps({
  productImage: {
    type: String,
    default: '/productdeal/image 3.svg'
  },
  productName: {
    type: String,
    default: 'Galaxy S22 Ultra'
  },
  currentPrice: {
    type: String,
    default: '₹32999'
  },
  originalPrice: {
    type: String,
    default: '₹74999'
  },
  saveAmount: {
    type: String,
    default: '₹32999'
  }
})
</script>

<style scoped>
.product-card {
  width: 234px;
  height: 340px;
  background-color: #FFFFFF;
  border: 1px solid #E0E0E0;
  border-radius: 8px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
}

.product-image {
  width: 100%;
  height: 180px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #F9F9F9;
  position: relative;
}

.product-image img {
  max-width: 80%;
  max-height: 80%;
  object-fit: contain;
}

.discount-badge {
  position: absolute;
  top: 0;
  right: 0;
  width: 51px;
  height: 53px;
  background-color: #008ECC;
  border-radius: 0 16px 0 16px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: #FFFFFF;
}

.discount-number {
  font-size: 16px;
  font-weight: 700;
  line-height: 1;
}

.discount-text {
  font-size: 12px;
  font-weight: 600;
  line-height: 1;
  margin-top: 2px;
}

.product-info {
  padding: 12px;
  display: flex;
  flex-direction: column;
}

.product-name {
  font-size: 16px;
  font-weight: 400;
  color: #000000;
  margin: 0 0 8px 0;
}

.price-container {
  display: flex;
  align-items: center;
  gap: 8px;
  margin-bottom: 8px;
}

.current-price {
  font-size: 18px;
  font-weight: 700;
  color: #000000;
}

.original-price {
  font-size: 14px;
  font-weight: 300;
  color: #666666;
  text-decoration: line-through;
}

.price-divider {
  width: 100%;
  height: 1px;
  background-color: #D9D9D9;
  border: none;
  margin: 8px 0;
}

.save-info {
  font-size: 14px;
  font-weight: 700;
  color: #249B3E;
}
</style>
