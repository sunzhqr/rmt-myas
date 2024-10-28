<template>
  <div class="poll-card">
    <h2>The most preferable programming language</h2>
    <img :src="progimg" alt="Programming Image" class="poll-image" />
    <p>Which programming language is the most useful?</p>
    <p>To conduct the research, our MYAS team needs you to make a choice</p>
    <p>#1 What programming language do you like?</p>
    <p>#2 What programming language do you use?</p>
    <div class="button-group">
      <button class="description-button">Description</button>
      <button class="vote-button">Vote</button>
    </div>
  </div>
</template>

<script>
import progimg from '../assets/progimg.jpg';

export default {
  data() {
    return {
      progimg,
    };
  },
};
</script>

<style scoped>
.poll-card {
  background-color: #2b4f80;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
  color: #ffffff;
  max-width: 400px; /* Уменьшенная ширина */
  flex: 1;
}

.poll-image {
  width: 100%;
  max-height: 250px; /* Максимальная высота для уменьшения размера */
  height: auto;
  border-radius: 8px;
  margin-top: 10px;
  margin-bottom: 10px;
  object-fit: cover; /* Обрезка, если изображение превышает размер */
}

.button-group {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin-top: 20px;
}

.description-button, .vote-button {
  background-color: #3d6a9c;
  color: #ffffff;
  border: none;
  padding: 8px 16px;
  border-radius: 5px;
  font-size: 14px;
  cursor: pointer;
}

.description-button {
  background-color: rgba(255, 255, 255, 0.1);
}

.vote-button {
  background-color: #4a6fa5;
}

.vote-button:hover, .description-button:hover {
  background-color: #5b86c2;
}
</style>
