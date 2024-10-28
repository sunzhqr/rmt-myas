<template>
  <aside class="sidebar">
    <div class="menu-item">
      <i class="icon">⭐</i> Profile
    </div>
    <div class="menu-item">
      <i class="icon">🕒</i> History
    </div>
    <div class="menu-item">
      <i class="icon">📊</i> Create a poll
    </div>
    <div class="menu-item">
      <i class="icon">🏢</i> Organization
    </div>
  </aside>
</template>

<script>
export default {};
</script>

<style scoped>
.sidebar {
  background-color: #1a2b48;
  border-radius: 10px;
  padding: 20px;
  color: #ffffff;
  width: 180px; /* Уменьшенная ширина */
  align-self: flex-start; /* Выравнивание в начало */
  margin-top: 10px;
}

.menu-item {
  display: flex;
  align-items: center;
  padding: 10px 0;
  font-size: 1rem;
  cursor: pointer;
}

.icon {
  font-size: 1.2rem;
  margin-right: 10px;
}
</style>
