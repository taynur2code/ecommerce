<template>
  <div class="essentials-card-wrapper">
    <div class="essentials-card">
      <div class="card-content">
        <img :src="productImage" alt="Product">
      </div>
    </div>
    <p class="card-title">{{ cardTitle }}</p>
    <p class="card-discount">UP to 50% OFF</p>
  </div>
</template>

<script setup>
import { defineProps } from 'vue'

const props = defineProps({
  productImage: {
    type: String,
    required: true
  },
  cardTitle: {
    type: String,
    default: 'Daily Essentials'
  }
})
</script>

<style scoped>
.essentials-card-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.essentials-card {
  width: 187px;
  height: 187px;
  background-color: #F3F3F3;
  border: 1px solid #E0E0E0;
  border-radius: 8px;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
}

.card-content {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.card-content img {
  max-width: 80%;
  max-height: 80%;
  object-fit: contain;
}

.card-title {
  margin: 12px 0 4px 0;
  width: 112px;
  height: 20px;
  font-size: 14px;
  font-weight: 500;
  color: #666666;
  text-align: center;
}

.card-discount {
  margin: 0;
  font-size: 16px;
  font-weight: 700;
  color: #222222;
  text-align: center;
}
</style>
