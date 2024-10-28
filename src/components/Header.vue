<template>
  <header class="header">
    <div class="logo-container">
      <img :src="avatar" alt="Avatar" class="avatar" />
      <div class="logo">MYAS (Magzhan, Yeltore, Ali, Sanzhar) Studio</div>
    </div>
    <button class="tutorial-button">Tutorial</button>
  </header>
</template>

<script>
import avatar from '../assets/obanai.jpg';

export default {
  data() {
    return {
      avatar,
    };
  },
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 30px;
  width: 100%;
  max-width: 1200px;
  background-color: #1a2b48;
  color: #ffffff;
}

.logo-container {
  display: flex;
  align-items: center;
  flex: 1;
  justify-content: center; /* Центрирование логотипа */
}

.avatar {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  margin-right: 12px;
  border: 2px solid #ffffff;
}

.logo {
  font-size: 1.2rem;
  font-weight: 500;
}

.tutorial-button {
  background-color: transparent;
  color: #ffffff;
  border: 1px solid #ffffff;
  padding: 5px 15px;
  border-radius: 5px;
  cursor: pointer;
  font-size: 14px;
  transition: background-color 0.3s;
}

.tutorial-button:hover {
  background-color: rgba(255, 255, 255, 0.2);
}
</style>
