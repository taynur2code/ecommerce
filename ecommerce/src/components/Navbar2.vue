<template>
  <div class="navbar2">
    <div class="hamburger-menu">
      <div class="line line1"></div>
      <div class="line line2"></div>
      <div class="line line3"></div>
    </div>
    <span class="megamart-text">MegaMart</span>
    
    <div class="search-box">
      <svg class="search-icon" width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
        <circle cx="8" cy="8" r="6" stroke="#00BECC" stroke-width="1.5"/>
        <path d="M12.5 12.5L16 16" stroke="#00BECC" stroke-width="1.5" stroke-linecap="round"/>
      </svg>
      <input type="text" placeholder="Search essentials, groceries and more..." class="search-input" />
      <svg class="filter-icon" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <circle cx="2" cy="12" r="1.5" fill="#00BECC"/>
        <line x1="7" y1="12" x2="23" y2="12" stroke="#00BECC" stroke-width="1.5"/>
        <circle cx="2" cy="6" r="1.5" fill="#00BECC"/>
        <line x1="7" y1="6" x2="23" y2="6" stroke="#00BECC" stroke-width="1.5"/>
        <circle cx="2" cy="18" r="1.5" fill="#00BECC"/>
        <line x1="7" y1="18" x2="23" y2="18" stroke="#00BECC" stroke-width="1.5"/>
      </svg>
    </div>
    
    <div class="user-section">
      <svg class="user-icon" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <circle cx="12" cy="8" r="4" stroke="#008ECC" stroke-width="1.5"/>
        <path d="M5 20C5 16.134 8.134 13 12 13C15.866 13 19 16.134 19 20" stroke="#008ECC" stroke-width="1.5" stroke-linecap="round"/>
      </svg>
      <span class="user-text">Sign Up / Sign In</span>
      <div class="divider-user"></div>
      <svg class="cart-icon" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1 1H4L6.68 14.39C6.77 14.84 7.17 15.17 7.63 15.17H19.4C19.86 15.17 20.26 14.84 20.35 14.39L22 6H6" stroke="#008ECC" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        <circle cx="9" cy="20" r="1.5" stroke="#008ECC" stroke-width="1.5"/>
        <circle cx="18" cy="20" r="1.5" stroke="#008ECC" stroke-width="1.5"/>
      </svg>
      <span class="cart-text">Cart</span>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
.navbar2 {
  width: 1440px;
  height: 90px;
  background-color: #FFFFFF;
  position: fixed;
  top: 42px;
  left: 0;
  right: 0;
  margin: 0;
}

.hamburger-menu {
  position: absolute;
  left: 120px;
  top: 21px;
  width: 48px;
  height: 48px;
  background-color: #F3F9FB;
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding-left: 11px;
  gap: 6px;
}

.line {
  height: 1.5px;
  background-color: #008ECC;
}

.line1 {
  width: 26px;
}

.line2 {
  width: 19px;
}

.line3 {
  width: 13px;
}

.megamart-text {
  position: absolute;
  left: 184px;
  top: 21px;
  font-size: 28px;
  color: #008ECC;
  font-weight: bold;
  line-height: 48px;
}

.search-box {
  position: absolute;
  left: 542px;
  top: 21px;
  width: 507px;
  height: 48px;
  background-color: #F3F9FB;
  border-radius: 10px;
  display: flex;
  align-items: center;
  padding: 0 15px;
  gap: 10px;
}

.search-icon {
  width: 18px;
  height: 18px;
  flex-shrink: 0;
}

.search-input {
  flex: 1;
  border: none;
  background: transparent;
  outline: none;
  font-size: 14px;
  color: #666666;
}

.search-input::placeholder {
  color: #666666;
}

.filter-icon {
  position: absolute;
  right: 15px;
  width: 24px;
  height: 24px;
  flex-shrink: 0;
}

.user-section {
  position: absolute;
  left: 1079px;
  top: 33px;
  display: flex;
  align-items: center;
  gap: 8px;
}

.user-icon {
  width: 24px;
  height: 24px;
}

.user-text {
  font-size: 14px;
  color: #666666;
  white-space: nowrap;
}

.divider-user {
  width: 1px;
  height: 24px;
  background-color: #D9D9D9;
  margin-left: 8px;
}

.cart-icon {
  width: 24px;
  height: 24px;
  margin-left: 8px;
}

.cart-text {
  font-size: 14px;
  color: #666666;
  white-space: nowrap;
}
</style>



