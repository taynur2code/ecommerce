<template>
  <div class="category-card">
    <div class="category-circle">
      <img :src="categoryImage" alt="Category">
    </div>
    <p class="category-name">{{ categoryName }}</p>
  </div>
</template>

<script setup>
import { defineProps } from 'vue'

const props = defineProps({
  categoryImage: {
    type: String,
    required: true
  },
  categoryName: {
    type: String,
    required: true
  }
})
</script>

<style scoped>
.category-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 12px;
}

.category-circle {
  width: 148px;
  height: 148px;
  border-radius: 50%;
  background-color: #F3F3F3;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.category-circle img {
  max-width: 70%;
  max-height: 70%;
  object-fit: contain;
}

.category-name {
  font-size: 16px;
  font-weight: 500;
  color: #000000;
  margin: 0;
  text-align: center;
}
</style>
