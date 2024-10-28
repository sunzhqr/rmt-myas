<template>
  <div id="app" class="app-container">
    <Header />
    <div class="content">
      <Sidebar />
      <PollCard />
      <RightInfo /> <!-- Блок справа -->
    </div>
  </div>
</template>

<script>
import Header from './Header.vue';
import Sidebar from './Sidebar.vue';
import PollCard from './PollCard.vue';
import RightInfo from './RightInfo.vue';

export default {
  components: {
    Header,
    Sidebar,
    PollCard,
    RightInfo,
  },
};
</script>

<style scoped>
.app-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #0f243f;
  color: #b3cde3;
  min-height: 100vh;
  width: 100%;
}

.content {
  display: flex;
  justify-content: center;
  width: 100%;
  max-width: 1200px;
  padding: 20px;
  gap: 30px;
}

</style>
