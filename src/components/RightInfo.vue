<template>
  <div class="right-info">
    <div class="info-item">
      <i class="icon">🛡️</i> trust in NEAR Blockchain
    </div>
    <div class="info-item">
      <i class="icon">🍕</i> 20 users has voted
    </div>
    <div class="info-item">
      <i class="icon">📢</i> quick view result
    </div>
    <ul class="result-list">
      <li>#1 Golang</li>
      <li>#2 Java</li>
      <li>#3 Python</li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.right-info {
  background-color: #1a2b48;
  border-radius: 10px;
  padding: 20px;
  color: #b3cde3;
  width: 250px;
  align-self: flex-start;
  margin-top: 10px;
}

.info-item {
  display: flex;
  align-items: center;
  font-size: 0.9rem;
  margin-bottom: 10px;
}

.icon {
  font-size: 1.2rem;
  margin-right: 8px;
}

.result-list {
  list-style-type: none;
  padding: 0;
  margin: 5px 0 0 24px; /* Отступ слева для выравнивания с текстом */
}

.result-list li {
  font-size: 0.9rem;
  color: #b3cde3;
}
</style>
