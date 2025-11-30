<template>
  <div class="card">
    <span class="welcome-text">Welcome to worlwide Megamart!</span>
    <div class="deliver-to">
      <img src="/Location.svg" alt="location" class="icon" />
      <span>Deliver to 423651</span>
    </div>
    <div class="divider-left"></div>
    <div class="track-order">
      <img src="/truck.svg" alt="truck" class="icon" />
      <span>Track your order</span>
    </div>
    <div class="divider"></div>
    <div class="all-offers">
      <img src="/Discount.png" alt="discount" class="icon" />
      <span>All Offers</span>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
.card {
  width: 1440px;
  height: 42px;
  background-color: #F5F5F5;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  margin: 0;
}

.welcome-text {
  position: absolute;
  left: 120px;
  top: 14px;
  font-size: 14px;
  color: #666666;
}

.deliver-to {
  position: absolute;
  left: 910px;
  top: 12px;
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 14px;
  color: #666666;
}

.divider-left {
  position: absolute;
  left: 1062.5px;
  top: 12px;
  width: 1px;
  height: 18px;
  background-color: #D9D9D9;
  border: 0.3px solid #D9D9D9;
  border-radius: 2px;
}

.track-order {
  position: absolute;
  left: 1078px;
  top: 12px;
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 14px;
  color: #666666;
}

.divider {
  position: absolute;
  left: 1222px;
  top: 12px;
  width: 1px;
  height: 18px;
  background-color: #D9D9D9;
  border: 0.3px solid #D9D9D9;
  border-radius: 2px; 
}

.all-offers {
  position: absolute;
  left: 1238px;
  top: 12px;
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 14px;
  color: #666666;
}

.icon {
  width: 16px;
  height: 16px;
}
</style>

