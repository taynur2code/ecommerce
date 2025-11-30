<template>
  <div class="category">
    <button class="groceries-btn">
      Groceries
      <svg width="14.9" height="8" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1 1L7.5 7L14 1" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
    <button class="category-btn">
      Premium Fruits
      <svg width="14.9" height="8" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1 1L7.5 7L14 1" stroke="#666666" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
    <button class="category-btn">
      Home & Kitchen
      <svg width="14.9" height="8" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1 1L7.5 7L14 1" stroke="#666666" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
    <button class="category-btn">
      Fashion
      <svg width="14.9" height="8" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1 1L7.5 7L14 1" stroke="#666666" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
    <button class="category-btn">
      Electronics
      <svg width="14.9" height="8" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1 1L7.5 7L14 1" stroke="#666666" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
    <button class="category-btn">
      Beauty
      <svg width="14.9" height="8" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1 1L7.5 7L14 1" stroke="#666666" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
    <button class="category-btn">
      Home Improvement
      <svg width="14.9" height="8" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1 1L7.5 7L14 1" stroke="#666666" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
    <button class="category-btn">
      Sports, Toys & Luggage
      <svg width="14.9" height="8" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1 1L7.5 7L14 1" stroke="#666666" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </button>
  </div>
</template>

<script setup>

</script>

<style scoped>
.category {
  width: 1440px;
  height: 69px;
  background-color: #FFFFFF;
  position: fixed;
  top: 132px;
  left: 0;
  right: 0;
  margin: 0;
  display: flex;
  align-items: center;
  gap: 8px;
  padding-left: 120px;
}

.groceries-btn {
  padding: 0 20px;
  height: 36px;
  background-color: #008ECC;
  border: none;
  border-radius: 18px;
  color: white;
  font-size: 14px;
  font-weight: 500;
  display: flex;
  align-items: center;
  gap: 8px;
  cursor: pointer;
}

.category-btn {
  padding: 0 20px;
  height: 36px;
  background-color: #F3F9FB;
  border: none;
  border-radius: 18px;
  color: #666666;
  font-size: 14px;
  font-weight: 500;
  cursor: pointer;
  white-space: nowrap;
  display: flex;
  align-items: center;
  gap: 8px;
}
</style>

